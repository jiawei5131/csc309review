### HTTP
1 **What is the internet?**
 * A collection of computer networks that use a protocol to exchange data.

2 **Internet Protocol (IP)**
 * Simple protocol for data exchange between computers
 * IP Addresses:
  * 32-bit for IPv5
  * 128-bit for IPv6

2 **Transmission Control Protocol (TCP)**
 * Adds multiplexing and reliable delivery on top of IP
  * Multiplexing: multiple programs using the same IP address
  * Reliability: guaranteed, ordered and error-checked delivery
 * Port: a number given to each program or service
  * port 80: web browser (port 443 for secure browsing)
  * port 25: email
  * port 22: ssh
 * Some programs (games, streaming media programs) use simpler UDP protocol instead of TCP

3 **Web Browser Vs Web Server**
 * Web Browser requests and parses documents from web servers
 * Web Server listens for web page requests

4 **Domain Name Server (DNS)**
 * Set of servers that map (translate) written names to IP addresses
  * Example: www.cs.toronto.edu → 128.100.3.40
 * Many systems maintain a local cache called a hosts file

5 **Uniform Resource Locator (URL)**
 * Identifies the path to a document on the web server
 * Upon entering this URL into the browser, it would:
  * ask the DNS server for the IP address of the URL
  * connect to that IP address at port 80
  * request the document from the server by sending
   * GET mashiyat/csc309/index.htm
  * parse and display the resulting page on the screen

6 **Hypertext Transport Protocol (HTTP)**
 * Set of commands understood by a web server and sent from a browser
 * Some HTTP commands (your browser sends these internally):
  * GET filename: download
  * POST filename: send a web form response
  * PUT filename: upload

7 **TCP/IP: Protocol Framework**

<table>
  <tr>
    <th>TCP/IP Layers</th>
    <th></th>
    <th colspan="4">TCP/IP Protocols</th>
  </tr>
  <tr>
    <td>Application Layer</td>
    <td></td>
    <td>HTTP</td>
    <td>FTP</td>
    <td>SMTP</td>
    <td>DNS</td>
  </tr>
  <tr>
    <td>Transport Layer</td>
    <td></td>
    <td>TCP</td>
    <td colspan="3">UDP</td>
  </tr>
  <tr>
    <td>Network Layer</td>
    <td></td>
    <td>IP</td>
    <td>ARP</td>
    <td>ICMP</td>
    <td>IGMP</td>
  </tr>
  <tr>
    <td>Network Interface Layer</td>
    <td></td>
    <td>Ethernet</td>
    <td>Token Ring</td>
    <td colspan="2">Other Link-Layer Protocols</td>
  </tr>
</table>

8 **TCP/IP**

9 **Types of Connection (TCP/UDP)**
* Connection oriented model
 * Like phone calls
 * Uses Transmission Control Protocol (TCP)
 * Defined ordering of messages and acks
* Connectionless model
 * Like sending letters via postal service
 * Uses User Datagram Protocol (UDP)
 * More efficient and good for sending broadcasts to many machines

### HTML
1. Hypertext Markup Language (HTML)
 * Describes the content and structure of information on a web page
 * Not the same as the presentation (appearance on screen)
 * Surrounds text content with opening and closing tags
 * Each tag's name is called an element

### LESS & SASS
CSS Pre-processor: converts code written in a preprocessec language to CSS
* DRY principle (don't repeat yourself)
 * Variables
 * Minxins
 * Functions
* Maintainability
* Readability
* Natural Extension
* You	can	change	the	extension	of	.CSS	files	to	.LESS	and	start	typing	LESS	
• You	can	define	namespaces	similar	to	C/C++	that	can	ignore	variables?	
• You	can	use	CSS	funcBons	by	escaping	them
