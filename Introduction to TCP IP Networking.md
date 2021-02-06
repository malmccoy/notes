# Introduction to TCP/IP Networking

## Quiz Answers and Explanations

 1. **TCP** (Transmission Control Protocol) and **UDP** (User Datagram Protocol) are examples of TCP/IP transport layer protocols.
| TCP/IP Architecture Layer | Example Protocols        |
| :-------------            | :----------:             |
| Application               | HTTP, POP3, SMTP         |
| Network                   | TCP, UDP                 |
| Transport                 | IP, ICMP                 |
| Data Link & Physical      | Ethernet, 802.11 (Wi-Fi) |
 2. **Ethernet** and **PPP** are examples of data-link protocols.
 3. The process of HTTP asking TCP to send some data and making sure it's recieved correctly is an example of **adjacent-layer interaction**.
 4. The process of TCP on one computer marking a TCP segment as segment 1, and the receiving computer then acknoeledging the receipt of TCP segment 1 is an example of **same-layer interaction**.
 5. The process of a web server adding a TCP header to the contents of a web page, followed by adding an IP header and then adding a data-link header and trailer, is an example of **data encapsulation**.
 6. **Frame** identifies the entity created when encapsulating data inside the data-link layer headers and trailers.
 7. **Layer 2 PDU** can be used instead of the term frame.
 
 # Key Terms
 
- adjacent-layer interaction - when one layer of the OSI model communicates with the one above or below it 
- de-encapsulation - removing headers (and sometimes trailers) around some data. Essentially, moving up the OSI model.
- encapsulation - adding headers (and sometimes trailers) around some date. Essentially, moving down the OSI model.
- frame - L2PDU (data of the data-link layer)
- networking model - any group of protocols and standards that allow devices to communicate e.g. TCP/IP and OSI
- packet - L3PDU (data of the network layer)
- protocol data unit (PDU) - OSI model headers, trailers, and the data they encapsulate
- same-layer interaction - interactions on the same layer of the network model by different devices
- segment - L4PDU (data of the transport layer)
