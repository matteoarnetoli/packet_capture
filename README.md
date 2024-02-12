<h1>Capturing TCP/IP Packets Using Wireshark</h1>


<h2>Project description and scenario</h2>

I am a junior cybersecurity analyst working for a small company. Today I was assigned the task to monitor TCP/IP network traffic. The IT manager asked me to capture and observe Ethernet packets on HTTP and HTTPS ports and detect traffic coming from certain IP addresses. The company is mostly interested in looking for inappropriate access to external websites from the server.
<br />

<h2>Project walk-through:</h2>

<h3><p align="center">Create a filter to only display port 80 TCP data:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/b2630eb7-8af1-4e69-a896-feac18e6b8b2">

<h3><p align="center">Create a filter to display only HTTP and HTTPS packets:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/b39d56ca-1e3f-498b-bdb9-da4ff35b8327">

<h3><p align="center">Omit visits to a specific IP address from the displayed packets:</h3>

<p align="center"><img width="70%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/f502eceb-c017-4178-b376-4a4d67106e70">



