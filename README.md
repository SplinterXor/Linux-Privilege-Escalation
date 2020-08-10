Linux Privilege Escalation
--------------------------

<Fixing a Shell>
Mirror the victims machine with your kali terminal window
  
  $ stty -a  <br>
  $ stty raw -echo <br>
  ** $ fg
  $ stty rows <number> columns <number>
  $ reset
  $ export TERM=screen
  $ export SHELL=bash


