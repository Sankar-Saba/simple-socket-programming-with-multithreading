# simple-socket-programming-with-multithreading
A sample program to explain socket programming, multi threading

server.cpp
simple program to implement
  Socket creation:  int sockfd = socket(domain, type, protocol)
  Setsockopt: int setsockopt(int sockfd, int level, int optname,const void *optval, socklen_t optlen);
  Bind: int bind(int sockfd, const struct sockaddr *addr, socklen_t addrlen);
  Listen: int listen(int sockfd, int backlog);
  Accept: int new_socket= accept(int sockfd, struct sockaddr *addr, socklen_t *addrlen);
  Write : writing the counter by every one second
  
client.cpp
simple program to implement
  Socket connection: 
  Connect:int connect(int sockfd, const struct sockaddr *addr,socklen_t addrlen);
  read & store the received data & pop-out every 10 sec
  
