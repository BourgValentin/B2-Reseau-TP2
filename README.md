# B2-Reseau-TP2

## I Mise en place du lab

### Capture des deux interfaces net2 et net12 sur router2
![Capture1](https://user-images.githubusercontent.com/35450078/54091603-4f7e5680-4382-11e9-9493-f2051439ce1a.PNG)

![Capture2](https://user-images.githubusercontent.com/35450078/54091615-6cb32500-4382-11e9-8fbe-0231348cb924.PNG)

#### On peut observer que la seule différence est le traffic ssh


## II NAT et services d'infra
### Nat
![Capture3](https://user-images.githubusercontent.com/35450078/54564102-3fdabf80-49cb-11e9-8220-78409f7ca6e4.PNG)

#### Toutes les machines peuvent joindre google.com, le nat est bien mis en place.

### DHCP
![Capture4](https://user-images.githubusercontent.com/35450078/54564107-410bec80-49cb-11e9-91bb-43d8d0c21c50.PNG)

#### Client2 a bien récupérer une adresse dans la plage indiquée et possède une route par défaut. Le dhcp est bien configuré.

### NTP
![Capture5](https://user-images.githubusercontent.com/35450078/54564109-423d1980-49cb-11e9-9d87-5cd8fb5a1f32.PNG)

#### La synchronisation NTP est bien active sur router2 et server1.
