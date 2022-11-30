## Lab 12

- Name: Donnell Smith
- Email: smith.2883@wright.edu

## Part 1 Answers:

1. `tar` options: retrieved from `man tar`
   - `-c` Create a new archive
   - `-v` Verbose output 
   - `-f` Use archive file
   - `-z` Filter the archive through gzip
   - `-x` Extract files from an archive
2. Command(s): tar -cvf Lab01.md ~/git_environment/CEG-2350-LABS/

## Part 2 Answers:

1. Command: sftp -i 2350key.pem ubuntu@54.145.149.159
2. `sftp` options: retrieved from `man sftp`
   - `ls` list directory contents
   - `lls` Display local directory listing of either path or current directory if path is not specified.
   - `put` Upload local-path and store it on the remote machine. If the remote path name is not specified, it is given the same name it has on the local machine. 
   - `get` Retrieve the remote-path and store it on the local machine.
3. Command(s): tar -f Lab01.md.tar.gz
4. Command(s): tar -x Lab01.md.tar.gz

## Part 3 Answers:

1. adduser JohnDoe
2. ssh-keygen -> 
3.
4.

## Part 4 Answers

1. Translate to network prefixes + CIDR notation:
   - Sample: `10.0.0.0 - 10.0.1.255` = `10.0.0.0/23` OR `10.0.1.0/23`
   - `130.108.0.0 - 130.108.255.255` =
   - `10.0.0.0 - 10.0.0.255` =
   - `your_public_ip - your_public_ip` =
2. How you confirmed current rules are bad, and why are they bad: By default, a security group includes an outbound rule that allows all outbound traffic and You can specify specific separate rules for inbound and outbound traffic are true: Default security groups allow all outbound traffic, and you specify separate inbound and outbound rules.
3. Your implementation details and **screenshot**
4. Something invalid: Valid IP address must be in the form of A.B.C.D, where A,B,C and D are numbers from 0-255. The numbers cannot be 0 prefixed unless they are 0.

## Extra Credit Answers:

### Solve the conflict

1.
2.
3.
4.
5.
