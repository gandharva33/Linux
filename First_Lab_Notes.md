1.echo 

echo simply repeats whatever you tell it to. It is case-sensitive echo,Echo and ECHO are all different.

Terminal:  echo "Hello World"

o/p : Hello World

2.whoami

It effectively asks the OS to identify the user account currently logged into the terminal session.It looks for the UserID associated with your active terminal process.

Terminal:  whoami

o/p:UserName

3.id

This command asks the system to report on your identity specifically,your UserID and the groups you belong to.

Terminal:  id

o/p: uid=5000(labex) gid=5000(labex) groups=5000(labex), 27(sudo), 121(ssl-cert), 5002(public)

uid = Your UserID (A unique numerical identifier)

gid = Your primary GroupID

groups = All the groups you are a member of.

Terminal : id root

o/p : uid =0(root) gid = 0(root) groups = 0(root)

root: It is an administrator or superuser in linux.

4.id -un

id -un prints only your username (the name for your current UID). 

Terminal:  id -un

o/p:UserName

