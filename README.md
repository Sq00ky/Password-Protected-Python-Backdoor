## Password Protected Backdoor

It's a simple password protected backdoor using subprocess to execute commands.
Instructions:
- Place on victim Linux box
- Create a service to ensure it's running at startup
- Use Netcat to connect to the Backdoor

So why use this over other methods?
Well, to be honest, you shouldn't lol. 
This is a more or less proof of concept for a King Of The Hill box for the Cyber Security training platform TryHackMe (https://tryhackme.com).

Note: Traffic is NOT encrypted and is in CLEARTEXT. This is NOT SECURE and should not be treated as such.

Created by Ronald Bartwitz

To do:
- [ ] Add support for Encryption
