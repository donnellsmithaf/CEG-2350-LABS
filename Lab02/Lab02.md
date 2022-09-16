## Lab 02

- Name: Donnell Smith
- Email: smith.2883@wright.edu

## Part 1 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub

1. Add a file for tracking: git add Lab02.md
2. Commit changes: git commit Lab02.md
<<<<<<< HEAD
3. Sync local commits with GitHub: git push git@github.com:donnellsmithaf/CEG-2350-LABS.git
=======
3. Sync local commits with GitHub: git push -u "git@github.com:donnellsmithaf/CEG-2350-LABS.git"
>>>>>>> bc6eebce2be9acc01e251868cb74053a651ab6b1

## Part 2 Answers

For each, write the command used or answer the question posed.

1. sudo adduser bob
2. pwd
3. Yes, because I am the administrator/ owner
4. su bob
5. cd /
6. Yes, its his account/ directory
7. exit
8. cd ~

## Part 3 Answers

For each, write the command used or answer the question posed.

1. sudo addgroup crew
2. usermod -a -G crew bob
3. 
4. su bob
5. touch bobsfile.txt
6. It was successful, because bob is a member of crew and crew has access to DirA and its contents 

## Part 4 Answers

For each, write the command used or answer the question posed.

1. sudo touch sudowho.txt
2. ls -lah (-rw-r--r--)
3. vim sudowho.txt (some text inserted) and to save I used :wq!

## Part 5 Answers

1. `ssh` command before configuring `config` file: ssh -i 2350key.pem ubuntu@54.145.149.159
2. HostName: ubuntu@ip-10-0-0-25
3. User: dsmith@DESKTOP-IV5MD8C
4. IdentityFile: ~/.ssh
5. `~/.ssh/config` contents: 

```
Paste your config file entry here
```

6. `ssh` command after configuring `config` file: alias aws= "ssh -i 2350key.pem ubuntu@54.145.149.159"
