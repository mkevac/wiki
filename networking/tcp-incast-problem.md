# TCP Incast problem

There is a problem specific to networking inside data centers that is caused by huge amount of messages sent to one server in a short bursts.

Small buffers on a network device \(switch\) causes packet loss and retransmissions which causes delays and possible further slowdown caused by resetting TCP window.

It can be mitigated by using different congestion control algorithms specifically designed for data centers.

{% hint style="info" %}
Main article: [http://bradhedlund.com/2011/05/01/tcp-incast-and-cloud-application-performance/](http://bradhedlund.com/2011/05/01/tcp-incast-and-cloud-application-performance/)

Video: [https://youtu.be/-e5Rw2I3QJk](https://youtu.be/-e5Rw2I3QJk)

Paper: [https://sci-hub.tw/10.1016/j.jnca.2019.102421 ](https://sci-hub.tw/10.1016/j.jnca.2019.102421%20)
{% endhint %}

