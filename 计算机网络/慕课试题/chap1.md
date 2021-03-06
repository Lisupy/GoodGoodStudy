1. 按照地理范围大小递增的顺序，给计算机网络排名。
    - [x] PAN, LAN, MAN, WAN
    - [ ] LAN, PAN, WAN, MAN
    - [ ] WAN, MAN, LAN, PAN
    - [ ] PAN, LAN, WAN, MAN

2. "HTTP, TCP, IP，PPP"是什么的例子?
    - [ ] 协议栈
    - [ ] 层
    - [ ] 参考模型
    - [x] 协议

3. 1500 字节的用户消息（信息）通过一个链路发送，在网络层和数据链路层分别使用 IP 和以太网协议，每层都有 20 字节的报头（其他层忽略不计）。协议报头开销占总带宽的比例是多少？
    - [x] 2.6%
    - [ ] 3.3%
    - [ ] 2.7%
    - [ ] 1.3%

4. 假设在一个内容源和三个内容消费者的正中间有一个装有副本的主机。通过使用副本分发目录，相比通过分别向三个消费者单独地分发目录，节约了多少网络资源？
    - [x] 33%
    - [ ] 25%
    - [ ] 50%
    - [ ] 66%
    
    > 让目录源和目录的使用者之间的路径变成一个单位的网络资源。然后发送三个独立副本需要3 个单位。使用副本，发送到副本需要 1/2 单元，从副本发送到这三个消费者需要 3* 1/2 单位，共需 2 个单位。我们节约了 1 / 3 单位或 33%。

5. 考虑一个主机通过两个路由器发送一个传输单元。用于发送用户消息的协议栈从顶部到底部依次是 TCP、 IP、 以太网。第一个路由器在IP层转发消息到WiFi 链路层。第二个路由器在IP层转发消息到 ADSL 链路层。
下面哪个选项是在第二个路由器之后的“线上”网络中看到的传输单元的最佳描述？字母表示协议头部，例如，T 为 TCP 头， M 代表用户消息。最左边部分首先出现在“线”上。
    - [ ] MTIE
    - [ ] AWEITM
    - [ ] MTIA
    - [x] AITM
    
    > 原始的以太网头部被ADSL头部替换。依据协议层次，路由器工作在IP层，终止输入链路层，以一个新的链路层代替。

6. 在网络上有一个1250字节的传输单元（已经封装好的PDU），它是利用DNS，UDP，IP，PPP，和SONET协议栈的一次用户发送消息的结果。每个协议报头是20字节长。携带此消息将使网络带宽的利用率达到多少？
    - [ ] 9%
    - [x] 92%
    - [ ] 98%
    - [ ] 50%

7. “线”上网络中进行的传输单元具有格式“ WiFi-header, IP-header, UDP-header, DNS-header, Message”，左边的项在“线”上首先出现。发送主机上什么样的**协议栈**会产生此传输单位？我们用每个报头的第一个字母来代表其相应的协议，例如，W 为WiFi产生的 WiFi-header。协议栈采用“自上而下”的顺序，在最上的部分我们写在最左边。
    - [ ] DUIW
    - [x] MDUIW
    - [ ] WIUDM
    - [ ] WIUD

    > 协议栈的顺序与封装的顺序相反。

8. Internet的核心协议是什么？
    - [x] TCP/IP
    - [ ] ARPANET
    - [ ] FTP
    - [ ] ISP

9. 在OSI参考模型上，物理层的功能是什么？
    - [ ] 建立和释放连接
    - [x] 透明地传输比特流
    - [ ] 在物理实体间传
    - [ ] 发送和接受用户数据