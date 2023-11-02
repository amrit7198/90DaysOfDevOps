# Day 6 Task: File Permissions and Access Control Lists

### Today is more on Reading, Learning and Implementing File permissions

The concept of Linux File permission and ownership is important in Linux.
Here, we will be working on Linux permissions and ownership and will do tasks on
both of them.
Let us start with the Permissions.

1. Create a simple file and do `ls -ltr` to see the details of the files [refer to Notes](https://github.com/LondheShubham153/90DaysOfDevOps/tree/master/2023/day06/notes)

Each of the three permissions are assigned to three defined categories of users. The categories are:

- owner — The owner of the file or application.
- "chown" is used to change the ownership permission of a file or directory.
- group — The group that owns the file or application.
- "chgrp" is used to change the group permission of a file or directory.
- others — All users with access to the system. (outised the users are in a group)
- "chmod" is used to change the other users permissions of a file or directory.

  As a task, change the user permissions of the file and note the changes after `ls -ltr`

2. Write an article about File Permissions based on your understanding from the notes.

   The file permissions can be viewed using the command 'ls -l'. It displays the permissions of each file in the format 'drwxrwxrwx:' format. These permissions cane be divided into three categories:

   *read permission: This permission allows any user to view the contents of any file or directory and they can copy the contents of this file also.

   *write permission: This permission allows the user to add, delete,or modify the contents of a file or directory.

   *execute permission: This permission allows any user to execute a script.

   We can divide the permissions of a particular file into sets of three such as'rwx,rwx,rwx'. The first set defines permission given to the user who created the file. The second set defines the permissions for the group to which the owner belongs to and the third set defines permissions for all the other users in the system. For example, in the notation 'r---w---x', the owner of the file only has the read permission, the group only has the write permission and all the other users have the execute permission.

   The individual file permissions can also be depicted emperically using some numbers. The read permission is assigned the number '4', the write permission is assigned the number '2' and the execute permission is assigned the number '1'. Using various combinations of the addition of these three numbers, we can define the permissions of a file. For example the number '7' will denote that the user has all the permissions for a file. Similarly, the number '5' will suggest that the user only has  the read and execute permissions.

4. Read about ACL and try out the commands `getfacl` and `setfacl`

In case of any doubts, post it on [Discord Community](https://discord.gg/hs3Pmc5F)

Happy Learning

[← Previous Day](../day05/README.md) | [Next Day →](../day07/README.md)
