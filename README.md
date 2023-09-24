Capturing and Analyzing TCP Traffic with Wireshark

Introduction

In this assignment, I will explore the process of capturing TCP (Transmission Control Protocol) traffic using Wireshark, a popular network protocol analyzer. This exercise will provide me with practical experience in analyzing network traffic.


Steps to Capture and Analyze TCP Traffic
In Wireshark, I selected the network interface I wanted to capture traffic from. I typically chose the interface that connects to the network I wanted to monitor. Then, I clicked the "Start" button to begin capturing traffic.
<img width="384" alt="image" src="https://github.com/ajmeraavi/assignment3_EntSWplat/assets/64644778/0f605ca6-f900-47ad-ba46-c23554fa5c8f">

I opened a new terminal window and used Netcat to create a TCP connection to a remote host and port. 
<img width="233" alt="image" src="https://github.com/ajmeraavi/assignment3_EntSWplat/assets/64644778/1aa4f973-f60f-4663-869c-cafd213060ad">

In the terminal where I initiated the Netcat connection, I typed and sent data. I knew that this data would be captured by Wireshark.
<img width="283" alt="image" src="https://github.com/ajmeraavi/assignment3_EntSWplat/assets/64644778/ca75b99c-e3c4-41bc-921d-b5098ba30ccc">

In Wireshark, I saw the captured TCP traffic. To inspect the payload, I selected a packet and looked at the "Packet Bytes" and "Packet Details" panes. I also right-clicked on a packet and chose "Follow" > "TCP Stream" to see the entire stream of data.

<img width="274" alt="image" src="https://github.com/ajmeraavi/assignment3_EntSWplat/assets/64644778/0f86e6fd-a576-46f8-80c7-91482d13980c">

In this assignment, I successfully captured and analyzed TCP traffic using Wireshark. I learned how to initiate a TCP connection, send data, and capture network traffic.

