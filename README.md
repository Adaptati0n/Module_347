# Module_347
Host my README


01
docker build -t my_app:latest . 
docker tag my_app:latest adaptati0n/my_app:01
docker run -p 3000:3000 my_app
docker push adaptati0n/my_app:01
docker scout recommendations my_app:01

Lien : https://hub.docker.com/layers/adaptati0n/my_app/01/images/sha256-0c0d191df4a31ccb077ef5b00b8c618dadb2f89a08c061a33b20c1806d824dff?context=repo

02
docker build -t my_app:latest . 
docker tag my_app:latest adaptati0n/my_app:02
docker run -p 3001:3000 my_app
docker push adaptati0n/my_app:02
docker scout recommendations my_app:02

Lien :https://hub.docker.com/layers/adaptati0n/my_app/02/images/sha256-a62a7c4043dfffdd6376ff3f1bacbd971aaaee3d2a4e140ee7117af7bd699525?context=repo

03
docker build -t my_app:latest . 
docker tag my_app:latest adaptati0n/my_app:03
docker run -p 3002:3000 my_app
docker push adaptati0n/my_app:03
docker scout recommendations my_app:03

Lien :

04

docker build -t my_app:latest . 
docker tag my_app:latest adaptati0n/my_app:04
docker run -p 3003:3000 my_app
docker push adaptati0n/my_app:04
docker scout recommendations my_app:04

Lien :

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
