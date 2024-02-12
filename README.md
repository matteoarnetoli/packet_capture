<h1>Capturing TCP/IP Packets Using Wireshark</h1>


<h2>Project description and scenario</h2>

I am a junior cybersecurity analyst working for a small company. Today I was assigned the task to monitor TCP/IP network traffic. The IT manager asked me to capture and observe Ethernet packets on HTTP and HTTPS ports and detect traffic coming from certain IP addresses. The company is mostly interested in looking for inappropriate access to external websites from the server.
<br />

<h2>Project walk-through:</h2>

<h3>Create a filter to only display HTTPS traffic:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/231d3497-f225-4fa4-87c8-5464b277bf52">

<h3>Open a packet and check relevant information:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/7dadadf5-7866-4f33-b9bc-8a0cdd4a2ba9">

<h3>Create a filter to display only HTTP and HTTPS packets:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/b39d56ca-1e3f-498b-bdb9-da4ff35b8327">

<h3>Omit visits to a specific IP address from the displayed packets:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/f502eceb-c017-4178-b376-4a4d67106e70">

<h3>Create a filter to only display TLS handshakes:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/ece4862a-a45e-47e7-a406-e4fff45d1d7e">








