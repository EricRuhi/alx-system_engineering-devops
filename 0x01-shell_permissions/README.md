su script is changing current user to betty
whoami script to show who the current user is
id -Gn script to print all the groups the current user is part of
sudo chown user file_script to change owner of file
touch hello script to create an empty file called hello
chmod 100 file_name script to add execute permission to the owner
chmod 554 script to ads execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod 755 to give user, group and other users execution permission
chmod 007 give user and group user 0 access and other user all the access
chmod 753 to give user all access, gruop user reading and execution acess and other user writing and execution permission
chmod u=rw,g=rw,o=r hello elloh to match modes
mkdir -m 751 my_dir to make directory and set it to mode 751
chgrp school hello script to change from current user to group school
sudo chown vincent:staff * to change owner and group owne
sudo chown -h vincent:staff _hello to change owner and owner group for symbolic link
sudo chown --from=<current_user> new_user file to change user only if user is specified
