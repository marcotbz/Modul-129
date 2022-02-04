# Dokumentation Labor 1 - Ping mit Switch

 - Datum: 14.01.2022
 - Name: Marco Nemeth
 - [Link zur Aufgabenstellung](https://gitlab.com/ch-tbz-it/Stud/m129/-/tree/main/07_GNS3%20Labor%20Anforderungen#2-labor-1-ping-mit-switch)

![GNS3 Screenshot meines Labors](images/Labor1.png)

## Cloud1
 - br0 192.168.23.129
 - Eigener PC ist via OpenVPN (Layer2) mit br0 verbunden. 

## Config VPC 1
- [GNS3 VPCS](https://docs.gns3.com/docs/emulators/vpcs/)
- 1x Ethernet Interface
```
set pcname PC1
ip 192.168.1.10 255.255.255.0
```

## Config VPC 2
- [GNS3 VPCS](https://docs.gns3.com/docs/emulators/vpcs/)
- 1x Ethernet Interface
```
set pcname PC2
ip 192.168.1.11 255.255.255.0
```

## Quellen
 - https://docs.gns3.com/docs/

## Neue Lerninhalte
 - GNS3

## Reflexion
Da diese Aufgabe nicht schwer war, habe ich mich eher mit dem User Interface von GNS3 beschäftigt und allgemein mich mit GNS3 etwas vertrauter gemacht.