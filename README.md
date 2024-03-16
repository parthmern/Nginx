# Nginx

- It is called Engin-x
- NGINX is a powerful web server known for its non-threaded, event-driven architecture.
- It excels in tasks like load balancing, HTTP caching, and functioning as a reverse proxy.
<br/>

### ❤️ Normal HTTP connection
- Still i know about nodeJs server where user directly make connection that knows as **Normal HTTP connection** here user is directly connected with server
- ![image](https://github.com/parthmern/Nginx/assets/125397720/2f5ee489-d7cd-47ce-af09-978487d287c0)
<br/>


### 🧡 Forward proxy
- while using VPN which is proxy server
- here *many clients* send request to vpn and then vpn sent that request to *one server* this is called **Forward proxy**
- here the server donot know the number of clients and which client is sending request on server.So for server there is only one client which is Vpn
- ![image](https://github.com/parthmern/Nginx/assets/125397720/20a1ebdb-8ba9-4b5d-a28c-7813b28bd674)
<br/>

### 💛 Reverse Proxy
- in **Reverse Proxy**, the number of *servers are multiple* but the number of *client is one*
- here in reverse proxy user donot know that the middle proxy send request on which server that user donot know
- ![image](https://github.com/parthmern/Nginx/assets/125397720/985bf728-4fbd-4397-b501-52a566419533)
- Most popular reverse proxy is ngnix
- ![image](https://github.com/parthmern/Nginx/assets/125397720/d55efdc6-5963-42d6-87fd-57648a0b2f0a)
  
- *reverse proxy*- here we are not giving access to the user to direct communication with server. user can communicate with ngnix/reverse proxy and here reverse proxy decides accroding to the code that by using which server client's request will be resolve
- *load balancing* - distributing load on different server using round robin algorithm
- *http caching* - first user put the req on ngnix for one image then server send that respone. after that when another user send the request for same image then ngnix can send that same image from cache so res is fast.
- ![image](https://github.com/parthmern/Nginx/assets/125397720/43458d5d-398f-4621-926e-3899c0efec8a)
- ![image](https://github.com/parthmern/Nginx/assets/125397720/d5f6fb98-02bd-46c2-b54c-7a2ea98a7f34)



