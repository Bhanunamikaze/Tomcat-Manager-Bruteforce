# Tomcat Manager Login Creds Bruteforce
This script will bruteforce the credential of tomcat manager or host-manager


## Default Paths
+ /manager/html: Default Tomcat Manager / Host Manager interface
+ /host-manager/html: Default Tomcat Manager / Host Manager interface 
+ /manager/status: Default Tomcat Server Status interface 
+ /host-manager/status: Default Tomcat Server Status interface 
+ Common Ports: 80, 443, 8080, 8081, 8181, 8888, 8989  

## Example:
```
python mgr_brute.py -u users.txt -p pass.txt -U http://10.10.10.194:8080/ -P host-manager/ 

```

## Screenshots

![image](https://user-images.githubusercontent.com/41506325/85556389-6a8edb80-b644-11ea-83e3-90050ec15705.png)
