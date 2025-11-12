# Observing-Computer-Traffic

<img width="474" height="296" alt="image" src="https://github.com/user-attachments/assets/cc357f5d-d596-47f6-b31a-ba409c2a4e3c" />



<h1>What is computer traffic and how to observe it</h1>
This brief walkthrough will allow someone to personally see data/traffic that is happening on the back end of a computer. All of the traffic that will be seen is the amount of data moving across a computer at any given time.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>prerequisites Required</h2>

- Virutal Machine

<h2>Steps to observing computer traffic</h2>

<img width="1632" height="932" alt="image" src="https://github.com/user-attachments/assets/d2834d9f-4cfa-45ec-bddf-ecf06ee4c74d" />

Install Wireshark on your virtual machine; it is a protocol analyzer, also called a packet snipper. This allows us to see all the traffic on the computer with our eyes. 
</p>
<br />

<img width="1033" height="586" alt="Screenshot 2025-11-11 182554" src="https://github.com/user-attachments/assets/d94ff292-65de-4f70-b290-a674d5725bcd" />
<img width="1626" height="922" alt="image" src="https://github.com/user-attachments/assets/d16287e4-ceed-4cef-836a-b7a4ac5a9bf6" />


Once you open the Wireshark file, keep clicking Yes and Next until you see NpCap. Make sure it's checked, then click Next. Do not check the USBPcap; proceed, and Wireshark should finish installing.  
</p>
<br />

<img width="1659" height="566" alt="Screenshot 2025-11-11 185506" src="https://github.com/user-attachments/assets/0f165214-5a09-4897-aaf7-25a6d6bed2e3" />
<img width="1666" height="1008" alt="Screenshot 2025-11-11 181020" src="https://github.com/user-attachments/assets/3842f83c-e6f2-4c57-affe-d43168a50a30" />

In Wireshark if you click on ethernet then the blue fin in the top left corner you will be able to see all the traffic within your computer.
</p>
<br />
