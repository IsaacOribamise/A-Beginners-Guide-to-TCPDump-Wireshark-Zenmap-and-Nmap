# Mastering-Network-Insights-A-beginners-guide-to-TCPDump-Wireshark-Zenmap-and-Nmap 📡🌐

<h2>📚 Introduction</h2>
Hey guys welcome to another cybersecurity project 🌐💻. In this project, I will dive into the basics of network security. TCPDump and Nmap are our tools of choice, this beginner's tool is essential in the monitoring and securing of our networks. Whether you're completely new to this or just curious to know more, this project is about the basics of keeping our network world safe and secure, so let's dive into it.

<h2>🛠️ Tools That I Used</h2>

- <b>[VirtualBox🔄-(Download the version for your operating system)](https://www.virtualbox.org/wiki/Downloads)</b>: This is an open-source virtualization platform that allows us to create and manage virtual machines (VMs). For our cybersecurity home lab, I would be using it to simulate diverse operating systems and network configurations within isolated environments.
- <b>[Kali Linux🏴‍☠️💻-(Download the VirtualBox 64-bit version)](https://www.kali.org/get-kali/#kali-virtual-machines)</b>: This is a Linux distribution designed for penetration testing, ethical hacking, and cybersecurity activities. In this home lab, I will use it as our primary toolkit for conducting security assessments, vulnerability analysis, and hands-on penetration testing exercises.
- <b>[Metasploitable 🎯-(The link downloads automatically)](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/metasploitable-linux-2.0.0.zip/download )</b>: This is a purposely vulnerable virtual machine designed for penetration testing and security training. I will use it to simulate a target environment with intentionally weak configurations and known vulnerabilities, making it an ideal resource for practicing ethical hacking techniques.

<h2>🔄💻 Required System Requirement: I use an HP ENVY x360 Laptop (Not the best but it does the job)</h2>

- <b>[🧠 CPU: 13th Gen Intel(R) Core(TM) i7-1355U 1.70 GHz (Anything higher than this will work)]</b>
- <b>[💾 RAM: 16GB (gigabytes) of RAM (I will say 8 GB of RAM or higher will suffice)]</b>
- <b>[📀 Disk: 1TB (Terabyte) (500GB - 1000GB of free disk space will be enough)]</b>
- <b>[🔄 BIOS/UEFI: VT-x, AMD-V, or the equivalent must be enabled in the BIOS/UEFI]</b>
- <b>[🔧 System Type: 64-bit operating system, x64-based processor (⚠️MANDATORY: This is a must)]</b>

<h2>[📝 Step by Step Guide To The Basics Using Nmap and TCPdump]

- <b>[THIS LINK IS A WELL-DETAILED GUIDE OF THE PROJECT](https://www.youtube.com/watch?v=wJ1orKMY2wc&list=PLUkY1OVVHzVktZOecfiDxdIodK4l5KkwY&index=7)</b>

- <b>📝 STEP 1: Download and install VirtualBox from the official website. Follow the installation instructions for your operating system.</b>

- <b>📝 STEP 2: Download and exact the Kali Linux and Metasploitable tool to use in Virtual box. </b>
<img width="617" alt="Screenshot 2023-12-31 060416" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/5e430e53-8f6e-46aa-afbf-338f59b5099c">


- <b>📝 STEP 3: After opening both tools, I ran 'ifconfig' on Metasploitable to know the IP address (172.20.10.13) I will be performing information gathering on. </b>
<img width="381" alt="Screenshot 2023-12-31 035106" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/4c795b36-9199-4ff4-9601-b0d85178522b">


- <b>📝 STEP 4: From here I was able to run basic Nmap commands on the command line to see what a vulnerable machine would look like. </b>
- For example: 'nmap 172.20.10.13' scans the top 1000 TCP ports on a target IP address, this tells us which ports are open or closed, and some open ports might mean a machine is vulnerable. just like our example in this project.
<img width="408" alt="Screenshot 2023-12-31 052449" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/1c1f6efa-95bb-4e3b-a6f3-45f33460770e">
- Another Nmap command I used was the 'nmap -O 172.20.10.13' which identifies the operating system of the target, for this machine it was a 'Linux 2.6.X'.
- Another Nmap command I experimented with was the 'nmap -sV 172.20.10.13' which shows the service versions running on open ports. For an attack information like this can be used to cause a lot of harm.


- <b>📝 STEP 5: I practiced using ZENMAP, which is just the GUI version of the Nmap. I practiced on the same IP address and this was my result </b>
<img width="609" alt="Screenshot 2023-12-31 054516" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/a5b4749f-f239-44c4-ad0b-21384db05f30">

- <b>📝 STEP 6: This was where I dived into TCPdump and practiced using its commands. The 'tcpdump -i eth0' captures packets on my network interface this essentially means that I can observe and analyze the data that is flowing through my computer's network connection.  </b>
<img width="419" alt="Screenshot 2023-12-31 055449" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/1e0821c2-72f7-4202-ad57-faaacca3e1ea">

- <b>📝 STEP 7: Lastly, I practiced the use of Wireshark, it has a similar function to the 'TCPdump' command which captures packets on my WIFI but is GUI version.
<img width="577" alt="Screenshot 2023-12-31 060146" src="https://github.com/IsaacOribamise/Mastering-Network-Insights-A-beginners-guide-to-TCPDump-and-Nmap/assets/154943957/077e2c6e-a1ae-4d74-b009-a1c2cdf40eef">

<h2>💡 key lessons and takeaways from this project:</h2>

I laid the foundation for a secure and controlled environment where I can explore, learn, and experiment with various cybersecurity tools and techniques. Understanding how the virtual world works, understanding these tools, and the purpose they serve. So stay tuned for more exciting projects that lie ahead! 🌐💻🚀


<h2> 🤳 Connect with me:</h2>

- Let's connect and share our passion for cybersecurity!
- Feel free to reach out for collaborations, discussions, or just to geek out over the latest exploits. 
- My LinkedIn page is below:

[<img align="left" alt="RichardSaunders | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://www.linkedin.com/in/isaac-oribamise/
