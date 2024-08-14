<h1> Home-Server-and-Client-setup</h1>

<h2><a href="https://www.youtube.com/watch?v=MHsI8hJmggI&list=PLqBeiU46hx1H--SNfTrohTOWeqkK-M2Y0">This is a Replication of Josh Madakor's tutorial </a></h2>

<h2>👨‍💻 Things you will need:</h2>

- <b>Choose the right server of your choice, in my case I choose Windows Server 2022</b>
- <b>Choose a desirable client, in my case I choose Windows 11</b>
- <b>Download the ISO images for the selected operating systems</b>
- <b>Domain Names, Passwords(since this was a home setup only going to be used for studying and experiments, weak passwords were choosen</b>
- <b>Obviously you will need a hypervisor, I choose Oracle Virtual Box as any other normal person would</b>

<h2>Network Topology</h2>

![image](https://github.com/user-attachments/assets/345505f5-a931-4c4a-b5d1-7c03f9e65e53)

<h2>Thing that were configured on my Domain controller</h2>

- <b>There will be a NAT that will be responsible to reach my home network and hence will be able to access the internet</b>
- <b>DNS and Active Directory was configured</b>
- <b>Created 1000 users using powershell</b>
- <b>DHCP was configured that will help my client computers to connect to my domain server</b>

<h2>Tips and trick that you might need:</h2>

- <b>You will need to install windows 11 without internet</b>
- <b>I felt like I was stuck and there are no options that you can click to proceed further connecting to a network</b>
- <b>Well there is..... use the shortcut shift + f10 to open command prompt and type in oobe\bypassnro</b>
- <b>This will restart and take you through the installation process again, but this time it will give you an option to continue without using any network connections</b>
