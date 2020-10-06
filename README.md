# min_ports.py
Given an input scan, find the minimum ports required to perform followup discovery scans

# Use an input file "external_audit.txt" in masscan format, e.g. 
Discovered open port 80/tcp on 192.168.1.1                                
Discovered open port 22/tcp on 192.168.1.1                               
Discovered open port 80/tcp on 192.168.1.2                              
Discovered open port 445/tcp on 192.168.1.3

# Output provides you with the minimum ports that would discover all hosts:
Nmap Friendly Output:
80,445

### Please don't judge my code quality....
