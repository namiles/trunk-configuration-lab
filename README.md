# Trunk Configuration Lab 
Full configuration for my Trunk configuration lab. All of the below command are ran in global config mode. See more at https://www.nicksnetworklab.com.

### S1
```
interface GigabitEthernet0/1
  switchport trunk allowed vlan 10,20,30,40
  switchport trunk encapsulation dot1q
  switchport mode trunk
```

### S2
```
interface FastEthernet0/1
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk

interface FastEthernet0/2
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk
```

### S3
```
interface FastEthernet0/1
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk

interface FastEthernet0/2
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk
```

### S4
```
interface FastEthernet0/1
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk

interface FastEthernet0/2
  switchport trunk allowed vlan 10,20,30,40
  switchport mode trunk
```
