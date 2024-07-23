<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Resources Needed for Lab (Virtual Machine using Windows 10/Virtual Network/Subnet and Linux (Ubuntu) VM/VNet/Subnet)
- Observe ICMP Traffic
- Observe SSH Traffic
- Observe DHCP Traffic
- Observe DNS Traffic
- Observe RDP Traffic

<h2>Actions and Observations</h2>

<p>
  
![Screen Shot 2024-07-22 at 7 56 45 PM](https://github.com/user-attachments/assets/d0045f11-5dac-44bf-b2e4-f02fa88d1cb7)
![Screen Shot 2024-07-22 at 7 57 32 PM](https://github.com/user-attachments/assets/3ab7b3d1-719a-4e70-b3f1-a64b01612237)
![Screen Shot 2024-07-22 at 7 57 49 PM](https://github.com/user-attachments/assets/138a83cf-7699-42e0-9872-688d17da257b)
</p>
<p>
In this step, we created resources needed to run the lab correctly.  The resources are a virtual machine using Windows 10, Virtual Network, and Subnet, and a Linux (Ubuntu) VM, VNet, and Subnet.
</p>
<br />



<p>
  
![Screen Shot 2024-07-22 at 8 09 10 PM](https://github.com/user-attachments/assets/3a49e175-f549-4d22-b4c9-f7b35895bb53)
![Screen Shot 2024-07-22 at 8 10 21 PM](https://github.com/user-attachments/assets/17e068f1-7d38-4e20-9f0a-d50ba5e1701d)
![Screen Shot 2024-07-22 at 8 10 51 PM](https://github.com/user-attachments/assets/51c71622-f3c4-4245-afc8-fe0ccb5de2c2)
![Screen Shot 2024-07-22 at 8 13 23 PM](https://github.com/user-attachments/assets/70156adb-b275-4911-8f47-ca518761bdee)
</p>
<p>
In this step, we observe ICMP traffic.
</p>
<br />



<p>

![Screen Shot 2024-07-22 at 8 17 42 PM](https://github.com/user-attachments/assets/994c90fa-a57f-4381-981c-5fab095c591c)
![Screen Shot 2024-07-22 at 8 18 12 PM](https://github.com/user-attachments/assets/e9b410cd-82bc-46fa-86a0-983ab9f8e74a)
</p>
<p>
In this step, we observe SSH traffic.
</p>
<br />



<p>
  
![Screen Shot 2024-07-22 at 8 36 51 PM](https://github.com/user-attachments/assets/878e15bb-927f-4e16-b79c-e6bd2e1c0799)
</p>
<p>
In this step, we observe DHCP traffic.
</p>
<br />



<p>
  
![Screen Shot 2024-07-22 at 8 41 04 PM](https://github.com/user-attachments/assets/ff0d87f4-b8a5-41f0-b648-a9edabb73ff9)
</p>
<p>
In this step, we observe DNS traffic.
</p>
<br />



<p>
  
![Screen Shot 2024-07-22 at 8 46 30 PM](https://github.com/user-attachments/assets/6afc214e-88de-4b00-abf4-5d8b7b14c95a)
![Screen Shot 2024-07-22 at 8 46 53 PM](https://github.com/user-attachments/assets/4035694f-e683-4b4f-86cf-bee54c14f82e)
</p>
<p>
In this step, we observe RDP traffic.
</p>
<br />

