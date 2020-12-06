## port_scanner ##

Parallel port scanner written in bash
### Usage ###
```
./port_scanner <host> <port | ports | portrange | a^> <no of processes>^^
```

  ^ 'a' should all 65535 ports have to be scanned  
  ^^ is optional, 100 processes will be utilized by default  

At the of the output is the -p flag with the list of opened ports, which can be later used with nmap command  

Examples:  
```
./port_scanner 10.10.113.371 a
```
```
./port_scanner 10.10.113.371 a 200
```
```
./port_scanner 10.10.113.371 1-1000
```
```
./port_scanner 10.10.113.371 22,80,443 
```

