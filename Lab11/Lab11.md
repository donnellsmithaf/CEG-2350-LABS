## Lab 11

- Name: Donnell Smith
- Email: smith.2883@wright.edu

## Part 1 Answers

1. Hostname of the device: DonnellSmithAF
2. MAC address of the NIC connected to the network: fe80::6d4d:9f8:5c5f:bee5%10
3. IP address: 76.190.80.35
4. Subnet mask: 255.255.0.0
5. Gateway address: 172.20.1.1
6. DHCP server address: 172.20.1.1
7. DNS server address: 172.20.1.1 
8. Public IP used for communications outside subnet: 172.20.9.193

## Part 2 Answers

1. `tcpdump` command: The "-w" option lets you write the output of tcpdump to a file which you can save for further analysis. The "-r" option lets you read the output of a file. All you have to do is use the "-r" option with tcpdump command and specify the path of the file you want to read.

   - How many packets were captured? 24402
   - Looking through the output, what traffic are you seeing? If your server initiates connections to an unknown host, it might be a sign that your server has been compromised. With the help of tcpdump and WinDump, you can easily capture outbound TCP packets on Linux and Windows.

2. Fancy `tcpdump` command: sudo tcpdump -i eth0 host www.google.com

3. Capturing `google.com` traffic:
   - Was there a difference in output from `curl` when using `http` or `https`? When Curl sends a request to an HTTPS URL, it checks the SSL certificate against the certificate store of the local CA.
   - Was there a difference in packet content in `tcpdump` when using `http` or `https`? TCPDUMP does the same job irrespective to what technology (or) server you are using it for.
   - What caused the difference? tcpdump is a data-network packet analyzer computer program that runs under a command line interface. curl command is a tool to download or transfer files/data from or to a server using FTP, HTTP, HTTPS, SCP, SFTP, SMB and other supported protocols on Linux or Unix-like system.
4. Save capture to a file:  
   Read capture from a file:  
   Don't forget to `commit` and `push` your capture to your `Lab11` folder.

## Part 3 Answers

1. Command(s) to install `python3` and `pip3`: sudo apt install python3, sudo apt install pip3
2. Run web server with `index.html` contents in your folder: python3 -m http.server 9000
3. Confirm content is being served: 
   - Using `localhost`:
   - Using the system's private IP:
   - Using the system's public IP:
4. What's playing? Rick Astley - Never Gonna Give You Up (Official Music Video), I found out by "cat"ing my index.html and finding the URL then copy and pasting it in my search bar.
5. Command to show `LISTEN`ing processes: lsof -i :80
6. Command to `kill`: kill all
