# XC-1.60-Full-Autoinstaller
Requirements
1. Dedicated server or VPS
2. Ubuntu 14.04 64 Bit as minimal clean installation

Installation
1. With putty login to your server root

2. Download and install the install Script:

< wget https://raw.githubusercontent.com/udoncyber/XC-1.60-Full-Autoinstaller/main/xtream-codes.sh

3. Set the permissions

< chmod 777 xtream-codes.sh

4. Start the install Script:

< ./xtream-codes.sh

5. Questions about updates all with Y confirm.

6. When requesting license from xtream panel, open winscp or other similar program and go to the folder located in [var / www / html / modules / servers / licensig] and edit the verify.php folder, and then I followed her <? php will paste this

 // If U Want Change Licenses Here, From Bubi1, 2, 3, etc. Insert Ur Name

<  $ Licenses = array ('bubi1');

7. back to putty license [bubi1]

8.fill the database password

9. fill the port

10. fill the panel password

11. rename the server

and the xtream codes 1.60 panel is installed
to go to the panel [ server ip: port you chose]

hope you like it
tested by me and working
