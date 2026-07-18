TCP Handshake Analysis

Goal
The purpose of this lab was to observe and analyze the TCP three-way handshake using Wireshark. The objective was to understand how a TCP connection is established between a client and a server.

Tool Used
- Wireshark

Procedure
The packet capture file example-traffic.pcapng was opened in Wireshark. TCP traffic was filtered to simplify the analysis. After filtering, the packets related to the connection establishment were examined.

Analysis

The captured traffic shows the standard TCP three-way handshake process.
First, the client initiated the connection by sending a SYN packet to the server.
The server responded with a SYN/ACK packet, indicating that it received the request and was ready to establish the connection.
Finally, the client replied with an ACK packet, completing the handshake.
This sequence confirms that the TCP connection was successfully established.

Evidence

The following screenshots were captured during the analysis:
- TCP traffic filtered in Wireshark (tcp-filter.png)
- TCP three-way handshake (tcp-handshake.png)

Conclusion
The analysis demonstrates the normal TCP connection establishment process. The packet capture contains all three required packets (SYN, SYN/ACK, and ACK), confirming that the connection between the client and the server was established successfully.
