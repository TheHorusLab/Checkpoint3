### Partie 1  
  
#### Q.2.1.1  
![reponse_2.1.1](https://github.com/user-attachments/assets/116c23bb-fb89-4c5a-a8b7-e002b7a1a1e7)  

#### Q.2.1.2  

Pour le compte créé je préconise de le mettre dans un groupe qui serait créé spécialement pour les comptes individuels avec les restrictions d'accès associés.  
Par exemple avec la commande : sudo usermod -aG Personnel john  

### Partie 2  
  
#### Q.2.2.1  
![reponse_2.2.1](https://github.com/user-attachments/assets/0586ecf7-bf61-49c7-84a1-8988e903d7ac)  
![reponse_2.2.1](https://github.com/user-attachments/assets/170834a5-c91a-4f6c-a6fa-179caafbe631)  

#### Q.2.2.2  
![reponse_2.2.2](https://github.com/user-attachments/assets/6f042ce1-306a-442e-8f92-811e9f17d45f)  
  

#### Q.2.2.3  
![reponse_2.2.3](https://github.com/user-attachments/assets/bfc9da51-c403-433e-ab13-1636781e7268)  

  
### Partie 3  

  
#### Q.2.3.1  

Systèmes de fichiers actuellement montés:  
-ext4 sur la partition /dev/mapper/cp--vg-root  
-ext2 sur la partition /dev/md0p1  
-swap sur la partition /dev/mapper/cp3--vg-swap_1  
  

#### Q.2.3.2  
  
Ils utilisent type de système de stockage LVM.  


### Partie 4  
  
  
### Partie 5  

#### Q2.5.1  

Les règles appliquées :  
En chaîne d'entrée, seul les connexions établies sont autorisés, celles invalides sont refusées.  
Les connexions en SSH avec le protocole TCP sur le port par défaut (22) sont autorisés  
Les requêtes utilisant le protocole ICMP en IPv4 sont autorisées.  
Les requêtes ICMPv6 avec le protocole de la couche supérieur sont autorisées.  
  
#### Q2.5.2  
  
Les types de communications autorisées : SSH en TCP sur le port par défaut (22)  

#### Q2.5.3  
  
Les types de communications interdits sont toutes celles qui ne sont pas déjà établie.  

#### Q2.5.4  

![reponse_2.5.4](https://github.com/user-attachments/assets/d7c1d02a-1d13-4381-9ac1-5d23ec49f544)  


