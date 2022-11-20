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

1. `tcpdump` command:

   - How many packets were captured? 24402
   - Looking through the output, what traffic are you seeing?

2. Fancy `tcpdump` command:

3. Capturing `google.com` traffic:
   - Was there a difference in output from `curl` when using `http` or `https`? When Curl sends a request to an HTTPS URL, it checks the SSL certificate against the certificate store of the local CA.
   - Was there a difference in packet content in `tcpdump` when using `http` or `https`? TCPDUMP does the same job irrespective to what technology (or) server you are using it for.
   - What caused the difference? 
4. Save capture to a file:  
   Read capture from a file:  
   Don't forget to `commit` and `push` your capture to your `Lab11` folder.

## Part 3 Answers

1. Command(s) to install `python3` and `pip3`:
2. Run web server with `index.html` contents in your folder:
3. Confirm content is being served:
   - Using `localhost`:
   - Using the system's private IP:
   - Using the system's public IP:
4. What's playing?
5. Command to show `LISTEN`ing processes:
6. Command to `kill`:

## Extra Credit Answers

1. How to find hostname for `EIP`:
2. Port scan command:
   - List of open ports:
3. How to view webpage:
4. Command to find SSH version:
   - Version information:
