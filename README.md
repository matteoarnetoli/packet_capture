![image](https://github.com/matteoarnetoli/packet_capture/assets/152484037/dd13f9b6-3cac-4944-ae00-f9ec5984bb65)![image](https://github.com/matteoarnetoli/packet_capture/assets/152484037/e34099f1-c67b-496f-bde8-e34ee71a21c2)<h1>Capturing TCP/IP Packets Using Wireshark</h1>


<h2>Project description and scenario</h2>

I am a junior cybersecurity analyst working for a small company. Today I was assigned the task to monitor TCP/IP network traffic. The IT manager asked me to capture and observe Ethernet packets on HTTP and HTTPS ports and detect traffic coming from certain IP addresses. The company is mostly interested in looking for inappropriate access to external websites from the server.
<br />

<h2>Project walk-through:</h2>

<h3><p align="center">Create a filter to only display port 80 TCP data:</h3>

<p align="center"><img width="60%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/0d23380d-c35d-44e4-b1cd-e9d66042235e">


<h3><p align="center">Create a filter to display only HTTP and HTTPS packets:</h3>

<p align="center"><img width="60%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/06d2bc79-5d7e-4493-9359-16abed44e783">

<h3><p align="center">Omit visits to a specific IP address from the displayed packets:</h3>

<p align="center"><img width="60%" alt="image" src="https://github.com/matteoarnetoli/packet_capture/assets/152484037/065ce2f3-2b3c-4bf8-b433-d5d98f5131b8">


