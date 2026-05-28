# Bandit Level 0 

## Objective
The goal of this challenge was to establish remote access using SSH and locate the entry-level flag.  

## Concepts covered
- SSH basics
- Reading files in linux

## My Approach
I connected to the server with SSH, listed the directory contents using `ls -la`, and read the readme file with `cat` to obtain the password for the next level

### Commands Used
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls -la
cat
```

## Key Takeaway 
Connecting to ssh needs a username and password to ensure the connection is safe because SSH uses asymmetric encryption to secure the transport layers, rendering credential sniffing useless to attackers on the local network, which is essential for secure cloud infrastructure administration and remote server management

## References 
I read an article from [It's Foss](https://itsfoss.com/ssh-to-port/) to broaden my knowledge on ssh connections and ports.
