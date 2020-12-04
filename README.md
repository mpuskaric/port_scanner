## port_scanner ##

Parallel port scanner written in bash
### Usage ###
./port_scanner <host> <port | ports | portrange>^
^ is optional, all 65535 ports will be scanned by default
at the of the output is the -p flag with the list of opened ports, which can be later used with nmap command
