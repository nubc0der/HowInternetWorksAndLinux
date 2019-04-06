#Linux
#ORIGIN
So it started in 1957 when Bell Labs found they needed an operating system for their computer center that at the time was running various batch jobs. The BESYS operating system was created at Bell Labs to deal with these needs. Bell Labs was adopting third generation computer equipment and decided to join forces with General Electric and MIT to create Multics (Multiplexed Information and Computing Service). By April of 1969, AT&T decided to withdraw Multics and go with GECOS. When Multics was withdrawn Ken Thompson and Dennis Ritchie needed to rewrite an operating system to play space travel on another smaller machine (a DEC PDP-7 [Programmed Data Processor 4 K memory for user programs). The result was a system that a punning colleague called UNICS (Uniplexed Information and Computing Service)--an 'emasculated Multics'. Then in the Summer of 1969 Unix was developed. Flash forward to a person named Linus Torvalds. At the time, he was a Computer Science undergraduate student at the University of Helsinki, Finland, and wanted a hobby project which he intended to release as a free OS. He had some technical differences with Minix and with its creator (Professor Andrew Tannenbaum, Computer Science, at a university in the Nederland), and so Linus wanted to do it his way and created Linux. Although very similar both languages have their branching paths but, today lets focus on linux and its commands.

-sources http://teaching.idallen.com/cst8207/11f/notes/02-Linux-History.pdf
https://www.computerhope.com/history/unix.htm

#Linux Commands
pwd — When you first open the terminal, you are in the home directory of your user. To know which directory you are in, you can use the “pwd” command.

cd — Use the "cd" command to go to a directory. For example, if you are in the home folder, and you want to go to the downloads folder, then you can type in “cd Downloads”. Remember, this command is case sensitive, and you have to type in the name of the folder exactly as it is.

File Permissions

chmod- Change access permission for a file(s).

chown	-Change the owner or group for a file.

ex:$ chmod -R www-data:www-data /var/www/html

vi-popular text editor on Unix-like operating systems. It can be used to edit all kinds of plain text and program files.

ex: $ vi filename

#File Transfer Protocol
FTP: is a client-server protocol that relies on two communications channels between client and server: a command channel for controlling the conversation and a data channel for transmitting file content. Clients initiate conversations with servers by requesting to download a file. Using FTP, a client can upload, download, delete, rename, move and copy files on a server

SFTP: SFTP, which stands for SSH File Transfer Protocol, or Secure File Transfer Protocol, is a separate protocol packaged with SSH that works in a similar way over a secure connection. The advantage is the ability to leverage a secure connection to transfer files and traverse the filesystem on both the local and remote system.
