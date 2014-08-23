Deity
=====

Deity is a kippo plugin that identifies dictionary attacks against it then issues 
the same attack against the attacker. After it gains access it can execute additional
commands.

Kippo: Is a ssh honeypot

Copy deity.py into kippo/dblog.
Added the following lines to your

```
[database_deity]
# Logfile
logfile = deity.log
# Amount of time to wait for connections (in seconds)
timeoutTime = 5
# Amount of failed attempts before attack
threshhold = 3

# To enable command file support uncomment to two lines below
# commandFile is the location of the file to read and execute
#commandFile = commands
#commandFileVerbose = True

#Below hasn't been implemented
# Save successful loggin to seperate file
successLog = False
```
