1 -FRISTLY I INSTALLED ANSIBLE-TEST BY YUM INSTALL
2 -THEN I UPDATED THE ANSIBLE INVENTORY WITH THE [HOSTNAME] [SALAHDIN] AND IP , AND [SLAHDIN:VAR] AND ADDED THE CREDINTIALS ANSIBLE USERNAME AND PASSWORD FOR SSH ACCESS
3- MY VERSION IS TEST SO IT NOT REQUIRED THEKEY CHECKING =FALSE BUT IN BORMAL WHAY IT REQIURED TO GET FALSE TO SKIP THE KEY CHECKING in ansible.cfg
4- I TESTED THE ANSIBLE CONNECTION WITH THE CLIENT WITH ANSIBLE SALAHDIN -M PING AND IT GIVE ME THE PONG
5- I WROTE THE YMEL FILE IT TAKE ME 22 TESTING FILE LIKE IN THE PICS ATTACHED
5- THE FIEREWALLED MODULE DOSENT EXESTED SO I INSTALLED IT BY ansible-galaxy collection install ansible.posix
6- FINLAAY I TESTED THE PHP FILE BY ANSIBLE URI MODULE AND IT FINAALY WORKED
7- I EXPERINCE A SPACING HELL AS ITS MY FIRST TIME YMEL BUT I AM REALLY HAPPY THAT I GAINED THIS WONDERFULL EXPERIENCE 3>>>>>>>>>>>>>>>>>>>>>>>>>>
:DDDDDDDDDDDDDDDDDD

commands
[root@SAlaHDIJN ansible]# yum install ansible
[root@SAlaHDIJN ansible]# ansible-playbook test22.yml
[root@SAlaHDIJN ansible]# ansible-galaxy collection install ansible.posix
[root@SAlaHDIJN ansible]# ansible salahdin -m ping

