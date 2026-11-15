# Task 7.1 - Explain newtwork concepts

 Concept | Explaination | Example |
|---|---|---|
| LAN | A network covering a small area, such as a home, lab or office. | Home Wi-Fi connecting a phone, laptop and printer. |
| MAN | A network covering a city or large campus area. | A fiber network linking a university's campuses across a city. |
| WAN | A network covering large geographical areas. | The Internet, or a bank linking branches in different countries. |
| DNS | Translates a domain name into an IP address. | Typing google.com and DNS returning its IP address. |
| Router | Connects networks and forwards data between them. | A home Wi-Fi router passing data between your devices and your ISP. |
| Protocol | A set of rules devices follow to communicate. | HTTPS for secure web browsing|
| Packet switching | Data is divided into packets that travel across a network. | An email split into packets that take different routes and are reassembled at the destination. |
| Client-server | A client requests a service and a server provides it. | A browser (client) requesting a web page from a web server. |


# Task 7.2 - Observe Network Information

Command 1: ping stackoverflow.com
command 2: nslookup stackoverflow.com

### Output
1. 64 bytes from 198.XXX.XXX.X: icmp_seq=0 ttl=59 time=5.896 ms
- 64 bytes from 198.XXX.XXX.X: icmp_seq=1 ttl=59 time=8.500 ms
- 64 bytes from 198.XXX.XXX.X: icmp_seq=2 ttl=59 time=4.418 ms
- 64 bytes from 198.XXX.XXX.X: icmp_seq=3 ttl=59 time=5.099 ms
- 64 bytes from 198.XXX.XXX.X: icmp_seq=4 ttl=59 time=8.459 ms
- 64 bytes from 198.XXX.XXX.X: icmp_seq=5 ttl=59 time=4.822 ms

2. Server:   [REDACTED]
- Address:  [REDACTED]

- Non-authoritative answer:
- Name:   stackoverflow.com
- Address: 198.252.206.1

1. What does a connectivity test help you check?
- It checks whether your computer can reach another computer over the network.

2. What information does a DNS lookup display?

- The domain name like asked about (stackoverflow.com)
- The IP address  that belong to that name
- Which DNS server answered 

3. What is the role of DNS when we enter a website name?
- DNS is  as a phone book for the internet. we know the name, but computers use IP addresses. The browser asks a DNS server for the IP address of that name. DNS replies with the address, and the browser uses it to connect to the website's server and load the page.


# Task 7.3 - What happens when we open a website.

1. As we type the website name (like stackoverflow.com) in the browser . My browser is the client because it asks for the page.

2. The browser asks DNS for the IP address.DNS works like a phone book: it changes the name into an IP address.

3. The browser sends a request using a protocol. It uses HTTPS, a protocol , to say, "Please send me this page."

4. The request travels through routers. It is split into packets, goes through the home router, then through many other routers on the Internet to the website.

5. The server receives the request. The server finds the web page that was asked for.

6. The server sends a response.The page's files (HTML, CSS, images) come back to the computer as packets.

7. The browser shows the page. My browser puts the files together and displays the website on the screen.

