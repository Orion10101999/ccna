##               Router
                    |
                    |
                    |
                    |
                    |
##               Switch
----------------------------------
|               |                |
|               |                |
Laptop 1      Laptop 2     Laptop 3


### Home City

### Corporate Office

### Laptops 

### Server Room (Main Wiring Closer)

### Router , Switch

##              Router
                    |   1.1.1.1
                    |   
                    |   Fa0/0
            Fa0/4   |
##              Switch
|----------------------------------|
|  Fa0/1        |  Fa0/2           |   Fa0/3
|               |                  |
|  Fa0          |  Fa0             |    Fa0
|               |                  |
Laptop 3      Laptop 4      Laptop 5
1.1.1.2     1.1.1.3    1.1.1.4      

1. no
2. enable
3. configure terminal
4. interface fa0/0
5. ip address   1.1.1.1 255.0.0.0
6. no shutdown
7. exit exit
8. router #
    show ip interface brief
9. 