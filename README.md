# Module_347
Host my README

Module 347 EPSIC 2024 Karim Jouini

## Image 01 : Q1 / Q2

### Question 1 :
1) Créer l’image Docker
```bash
docker build -t my_app:latest .
```
2) Taguer l’image pour DockerHub
```bash
docker tag my_app:latest adaptati0n/my_app:01
```
3) Lancer l’image dans un container
```bash
docker run -p 3000:3000 my_app:01
```
4) Pousser l’image sur DockerHub
```bash
docker push adaptati0n/my_app:01
```

### Question 2 :
![image](https://github.com/user-attachments/assets/ed9beb1e-feea-48e2-a9ed-385aa1c508d7)



Lien : https://hub.docker.com/layers/adaptati0n/my_app/01/images/sha256-0c0d191df4a31ccb077ef5b00b8c618dadb2f89a08c061a33b20c1806d824dff?context=repo


## Image 02 : Q1 / Q2 / Q3 / Q5

### Question 1 :

1) Créer l’image Docker
```bash
docker build -t my_app:02 .
```
2)
```bash
docker run -P -d --name my_app_container2 -v my_volume:/etc/todos adaptati0n/my_app:01  
docker run -p 3004:3000 -d --name my_app_container3 -v my_volume:/etc/todos adaptati0n/my_app:02
```
3) Taguer l’image 02 pour DockerHub
```bash
docker tag my_app:02 adaptati0n/my_app:02
```
4) Lancer l’image dans un container
```bash
docker run -p 3001:3000 my_app:02
```
5) Pousser l’image sur DockerHub
```bash
docker push adaptati0n/my_app:02
```
6) Scannez l'image
```bash
docker scout recommendations my_app:02
```
### Question 2 :
![image](https://github.com/user-attachments/assets/5b0dbf96-e6d8-4157-999f-80474ca9e5f3)


### Question 3 :
Il y'a eu 8 vulnérabilités, dont 6 considérées normal et 2 hautes. J'ai opté pour l'image [23-slim]

### Question 5 :
J'ai choisi l'image 23-slim car elle ne présente aucune vulnérabilité critique, élevée, ou moyenne, ce qui en fait un choix très sûr pour déployer une application en production. L'absence de vulnérabilités est cruciale pour garantir que notre application est protégée contre les cyberattaques potentielles et les failles de sécurité.

Lien : :https://hub.docker.com/layers/adaptati0n/my_app/02/images/sha256-a62a7c4043dfffdd6376ff3f1bacbd971aaaee3d2a4e140ee7117af7bd699525?context=repo


## Image 03 : Q1

### Question 1 :

1) Créer l’image Docker
```bash
docker build -t my_app:03 .
```
2) Taguer l’image 03 pour DockerHub
```bash
docker tag my_app:03 adaptati0n/my_app:03
```
3) Lancer l’image dans un container
```bash
docker run -p 3002:3000 my_app:03
```
4) Pousser l’image sur DockerHub
```bash
docker push adaptati0n/my_app:03
```
5) Scannez l'image
```bash
docker scout recommendations my_app:03
```

Im-3 :
![image](https://github.com/user-attachments/assets/5faf0760-9dc8-4ecc-9c4a-a4c5fda1658b)


Lien : https://hub.docker.com/layers/adaptati0n/my_app/03/images/sha256-eace4b745af002710e8d8a37d7aa19a55be780fb9a1bc3500c10bb242e75059c?context=repo


## Image 04 : Q1 

### Question 1 :

1) Créer l’image Docker
```bash
docker build -t my_app:04 .
```
2) Taguer l’image 04pour DockerHub
```bash
docker tag my_app:04 adaptati0n/my_app:04
```
3) Lancer l’image dans un container
```bash
docker run -p 3003:3000 my_app:04
```
4) Pousser l’image sur DockerHub
```bash
docker push adaptati0n/my_app:04
```
5) Scannez l'image
```bash
docker scout recommendations my_app:04
```

Im-4 :
![image](https://github.com/user-attachments/assets/c36641f9-0f0d-4e4e-8bb6-a3f8b5528970)



Lien : https://hub.docker.com/layers/adaptati0n/my_app/04-alpine/images/sha256-ff6b683caa84c2db7c188ed28d5e7dddfc976c3c597b9b60781af7f9fbaaee2e?context=repo

### Question 4 :

```bash
              Tag              │                  Details                  │    Pushed    │          Vulnerabilities
───────────────────────────────┼───────────────────────────────────────────┼──────────────┼─────────────────────────────────────
   23-slim                     │ Benefits:                                 │ 1 week ago   │    0C     0H     0M    23L 
  Tag is preferred tag         │ • Image is smaller by 259 MB              │              │    -6    -12     -6    +21 
  Also known as:               │ • Image contains 625 fewer packages       │              │
  • 23.1.0-slim                │ • Tag is preferred tag                    │              │
  • 23.1-slim                  │ • Major runtime version update            │              │
  • current-slim               │ • Tag was pushed more recently            │              │
  • slim                       │ • Tag is using slim variant               │              │
  • bookworm-slim              │                                           │              │
  • 23-bookworm-slim           │ Image details:                            │              │
  • 23.1-bookworm-slim         │ • Size: 80 MB                             │              │
  • 23.1.0-bookworm-slim       │ • Runtime: 22                             │              │
  • current-bookworm-slim      │                                           │              │
                               │                                           │              │
 ```
```bash
   18-slim                     │ Benefits:                                 │ 4 months ago │    0C     0H     0M    23L 
  Major runtime version update │ • Image is smaller by 269 MB              │              │    -6    -12     -6    +21 
  Also known as:               │ • Image contains 639 fewer packages       │              │
  • 18.20.4-slim               │ • Major runtime version update            │              │
  • 18.20-slim                 │ • Tag was pushed more recently            │              │
  • hydrogen-slim              │ • Tag is using slim variant               │              │
  • 18-bookworm-slim           │ • 18-slim was pulled 33K times last month │              │
  • 18.20-bookworm-slim        │                                           │              │
  • 18.20.4-bookworm-slim      │ Image details:                            │              │
  • hydrogen-bookworm-slim     │ • Size: 69 MB                             │              │
                               │ • Runtime: 18                             │              │
                               │                                           │              │
```

```bash
   22-slim                     │ Benefits:                                 │ 1 week ago   │    0C     0H     0M    23L 
  Major runtime version update │ • Image is smaller by 261 MB              │              │    -6    -12     -6    +21 
  Also known as:               │ • Image contains 625 fewer packages       │              │
  • 22.11.0-slim               │ • Major runtime version update            │              │
  • 22.11-slim                 │ • Tag was pushed more recently            │              │
  • lts-slim                   │ • Tag is using slim variant               │              │
  • jod-slim                   │                                           │              │
  • 22-bookworm-slim           │ Image details:                            │              │
  • lts-bookworm-slim          │ • Size: 78 MB                             │              │
  • jod-bookworm-slim          │ • Runtime: 22.11.0                        │              │
  • 22.11-bookworm-slim        │                                           │              │
  • 22.11.0-bookworm-slim      │                                           │              │
                               │                                           │              │
                               │                                           │              │
   20-slim                     │ Benefits:                                 │ 1 month ago  │    0C     0H     0M    23L 
  Major runtime version update │ • Image is smaller by 267 MB              │              │    -6    -12     -6    +21 
  Also known as:               │ • Image contains 644 fewer packages       │              │
  • 20.18.0-slim               │ • Major runtime version update            │              │
  • 20.18-slim                 │ • Tag was pushed more recently            │              │
  • iron-slim                  │ • Tag is using slim variant               │              │
  • 20-bookworm-slim           │                                           │              │
  • iron-bookworm-slim         │ Image details:                            │              │
  • 20.18-bookworm-slim        │ • Size: 72 MB                             │              │
  • 20.18.0-bookworm-slim      │ • Runtime: 20.18.0                        │              │

```
```bash
                               │                                           │              │
   23                          │ Benefits:                                 │ 1 week ago   │    0C     1H     3M   105L     3? 
  Tag is latest                │ • Image contains 202 fewer packages       │              │    -6    -11     -3   +103     +3 
  Also known as:               │ • Major runtime version update            │              │
  • 23.1.0                     │ • Tag was pushed more recently            │              │
  • 23.1                       │ • Image has similar size                  │              │
  • current                    │ • Tag is latest                           │              │
  • latest                     │                                           │              │
  • bookworm                   │ Image details:                            │              │
  • 23-bookworm                │ • Size: 407 MB                            │              │
  • 23.1-bookworm              │ • Runtime: 22                             │              │
  • 23.1.0-bookworm            │                                           │              │
  • current-bookworm           │                                           │              │

```
```bash
   18                          │ Benefits:                                 │ 4 months ago │    0C     1H     3M   105L     3? 
  Major runtime version update │ • Image contains 216 fewer packages       │              │    -6    -11     -3   +103     +3 
  Also known as:               │ • Major runtime version update            │              │
  • 18.20.4                    │ • Tag was pushed more recently            │              │
  • 18.20                      │ • Image has similar size                  │              │
  • hydrogen                   │ • 18 was pulled 160K times last month     │              │
  • 18-bookworm                │                                           │              │
  • 18.20-bookworm             │ Image details:                            │              │
  • 18.20.4-bookworm           │ • Size: 396 MB                            │              │
  • hydrogen-bookworm          │ • Runtime: 18                             │              │
```
```bash
                               │                                           │              │
   22                          │ Benefits:                                 │ 1 week ago   │    0C     1H     3M   105L     3? 
  Major runtime version update │ • Image contains 202 fewer packages       │              │    -6    -11     -3   +103     +3 
  Also known as:               │ • Major runtime version update            │              │
  • 22.11.0                    │ • Tag was pushed more recently            │              │
  • 22.11                      │ • Image has similar size                  │              │
  • lts                        │                                           │              │
  • jod                        │ Image details:                            │              │
  • lts-jod                    │ • Size: 405 MB                            │              │
  • 22-bookworm                │ • Runtime: 22.11.0                        │              │
  • lts-bookworm               │                                           │              │
  • jod-bookworm               │                                           │              │
  • 22.11-bookworm             │                                           │              │
  • 22.11.0-bookworm           │                                           │              │
```
```bash
   20                          │ Benefits:                                 │ 1 month ago  │    0C     1H     3M   105L     3?
  Major runtime version update │ • Image contains 221 fewer packages       │              │    -6    -11     -3   +103     +3
  Also known as:               │ • Major runtime version update            │              │
  • 20.18.0                    │ • Tag was pushed more recently            │              │
  • 20.18                      │ • Image has similar size                  │              │
  • iron                       │                                           │              │
  • 20-bookworm                │ Image details:                            │              │
  • iron-bookworm              │ • Size: 399 MB                            │              │
  • 20.18-bookworm             │ • Runtime: 20.18.0                        │              │
  • 20.18.0-bookworm           │                                           │              │
                               │                                           │              │
                               │                                           │              │
```
```bash
Question 6:

Image Choisie : node:23-alpine
Pourquoi node:23-alpine ?

Légèreté et Rapidité :

L'image alpine est une version minimaliste de Linux qui est connue pour sa taille extrêmement réduite. Cela signifie que l'image est plus petite, ce qui permet un démarrage et un déploiement plus rapides des conteneurs. En comparaison avec les images complètes, node:23-alpine peut réduire considérablement la consommation de ressources.
Sécurité Améliorée :

Avec moins de paquets et de dépendances installés par défaut, l'image alpine réduit la surface d'attaque potentielle. Cela signifie qu'il y a moins de vulnérabilités exploitables par des attaquants, ce qui en fait un choix plus sécurisé pour des applications déployées en production.
Optimisation des Ressources :

L'image node:23-alpine consomme moins de mémoire et d'espace disque, ce qui est particulièrement avantageux pour les environnements où les ressources sont limitées. Cela aide également à améliorer l'efficacité globale de l'application.
Avantages de l'Image node:23-alpine
Taille Réduite : L'image alpine est significativement plus petite que les versions complètes, ce qui diminue les coûts de stockage et améliore les performances de téléchargement et de déploiement.
Sécurité : Moins de composants signifie moins de vulnérabilités potentielles, et l'image est régulièrement mise à jour pour inclure les derniers correctifs de sécurité.
Performance : Démarrage rapide des conteneurs, ce qui est crucial pour des applications nécessitant une mise en ligne rapide.

```
