#shell permissions

su user: switch user

whoami: print the current user

groups: see all the groups the current user is part of

chown: change the owner of the file

touch: create empty file

chmod u+x: add execute permission to the owner

chmod ug+x: add execute permission to the owner and the group owner

chmod a+x: add execute permission to all users

chmod 007: add execute permission to all users except owner and the group owner

chmod 753: add read ,write,execute permission to the owner and read , excute permission to the group owner and write, execut to other

chmod 354: match the file 'olleh'

chmod -R ugo+X .: add execute permission to all subdirectories of the current directory

mkdir -m 751: create directory with permissions

chgrp: change the group ownership

#Advanced Tasks

chown -R vincent:staff: change the owner and the group owner

chown -R vincent:staff _hello: change the owner and the group owner of file

chown --from=guillaume betty hello: change owner only if match

telnet towel.blinkenlights.nl: play Star Wars IV episode :)