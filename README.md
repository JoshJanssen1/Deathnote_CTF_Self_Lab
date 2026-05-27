# Deathnote_CTF_Self_Lab
A Deathnote-inspired CTF virtual machine. 

## Virtual Machines and tools used
Kali Linux - attacking machine
Deathnote VM (Vulnhub Vm)https://www.vulnhub.com/entry/deathnote-1,739/

## Tools Used
Nano, dirb, gobuster,ferobuster, hydra, SSH

# Goal
To use Kali Linux to gain access to the Deathnote VM, gain root access, and complete the CTF-type activity.

# Lessons Learned
I completed the Deathnote VM from VulnHub as a hands-on penetration testing and enumeration exercise. The lab focused heavily on reconnaissance, web enumeration, credential discovery, and privilege escalation techniques in a Linux environment. 

After obtaining a foothold, I conducted local enumeration to identify privilege escalation vectors, including file permissions, sudo rights, scheduled tasks, and misconfigurations. I successfully escalated privileges to root by exploiting insecure system configurations.

