# python-networking
Repository with basic python programs with application of computer networking


In Python, the socket library provides a number of attributes that can be used to manipulate and configure sockets.
Here are some of the most commonly used attributes:
- AF_INET - Address family for Internet Protocol version 4 (IPv4) addresses.
- AF_INET6 - Address family for Internet Protocol version 6 (IPv6) addresses.
- SOCK_STREAM - Type of socket that provides reliable, stream-oriented communication.
- SOCK_DGRAM - Type of socket that provides unreliable, datagram-oriented communication.
- SOCK_RAW - Type of socket that provides raw access to the network stack.
- IPPROTO_TCP - Protocol number for the Transmission Control Protocol (TCP).
- IPPROTO_UDP - Protocol number for the User Datagram Protocol (UDP).
- SOL_SOCKET - Socket level option that can be used with the setsockopt() and getsockopt() methods.
- SO_REUSEADDR - Option that allows multiple sockets to bind to the same address and port.
- SO_BROADCAST - Option that allows sending of broadcast messages.
- SO_RCVBUF - Option that specifies the receive buffer size.
- SO_SNDBUF - Option that specifies the send buffer size.
- SO_LINGER - Option that specifies whether to linger on close.
- SO_ERROR - Option that retrieves the error status of the socket.
- SO_TYPE - Option that retrieves the socket type.
- SOCKET_ERROR - A constant that indicates an error in socket operations.
- INADDR_ANY - A constant that specifies that the socket can accept connections from any network interface.
- INADDR_LOOPBACK - A constant that specifies the loopback interface.

### Note that this is not an exhaustive list, and the socket library provides many more attributes that can be used depending on the specific use case.
