shell permisions
0  change file user :  su new user name
1 show current user : whoami
2 show all grouos im part of : groups
3 change owner of the file : sudo shown new user  file
4 create a new file called hello " touch hello" 
5 add exec perm to the oxner of the file : chmod u+x
6 add exec to all groups and read to others : chmod u+x,g+x,o+r name_file
7 add exec for all ( owner , group owner and others) : chmod a+x namefile
8 set permissions for owner, group and other , chmod 007
9 transfer code RWX to binary code for chmod
10 set file perm the same as file y : chmod --reference=filey filex
11 Add X to all subdirectories for all : chmod -R a+X .
12 create a dir with 751 perm mkdir -m 751 my-dir
13 change grp ownership : chgrp school (owner) hello (file)
14 change owner and grp owner ; chown owner:groupowner * (for all dir and files in working dir
15 change owner and grp owner to a specific gtoup chow -h (specified file) owner:grpowner file
16 change the owner of the file only if the owner is x : chown --from=x newoner file
  
