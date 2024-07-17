### Socket
[详细文档](https://pubs.opengroup.org/onlinepubs/7908799/xns/syssocket.h.html)

#### socket创建的参数

int socket(int domain, int type, int protocol)

> 参数介绍：
domain：协议域，（常见的协议组用AF_INET、AF_INET6、AF_LOCAL、AF_ROUTE）协议族决定了socket的地址类型，在通信中必须采用相应的地址；

type：socket的类型，（流格式套接字(SOCK_STREAM)、数据报格式套接字(SOCK_DGRAM)）；

protocol：协议，常见的协议有IPPROTO_TCP、IPPTOTO_UDP、 IPPROTO_SCTP、IPPROTO_TIPC他们分别对应这TCP传输协议、UDP传输协议、STCP传输协议、TIPC传输协议。当protocol为0时，会自动选择type类型对应的默认协议；

返回值：
返回一个文件描述符，SOCKET类型本身也是定义为int的，既然是文件描述符，那么在系统中都当作是文件来对待的。0、1、2分别表示标准输入、标准输出、标准错误。所以其他打开的文件描述符都会大于2， 错误时就返回 -1。这里INVALID_SOCKET 也被定义为 -1。
*/


#### 如何关闭已经阻塞的Socket线程
```c
shutdown(pre_sock,SHUT_RDWR);
close(pre_sock);
```