cat /etc/passwd

login
root toor
exit

root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin

backdoor vulnerability:
assiging a user with 0 id makes him root - hard to detect...

useradd -m username -s /bin/bash
passwd username // assign pass to user

passwd -d user // no pass

תצורו את המשתמש helpdesk ואל תשכחו להגדיר למשתמש תיקיית בית.
2 .הכניסו את המשתמש לקבוצת sudo.
3 .בצעו את הפקודה
sudo vi /etc/passwd
4 .שנו את ה-id של המשתמש helpdesk ל-0 והתחברו למשתמש

useradd -m helpdesk -d /helpdesk -s /bin/bash
adduser helpdesk sudo
sudo vi /etc/passwd
