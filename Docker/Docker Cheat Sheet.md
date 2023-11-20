<center><font size='30'>Docker Cheat Sheet</font></center>

```mermaid
flowchart TB
C((Docker CLI))
MI([Manage Images])
IC([Inspecting Containers])
MC([Manage Containers])
IB([Image Builder])
C-->MI
C-->MC
C-->IC
C-->IB
MI-->a(docker history)
MI-->b(docker commit)
MC-->c(docker pause)
MC-->d(docker container ls)
IC-->e(docker ps)
IC-->f(docker top)
IB-->g(docker buildx)
IB-->h(docker build)
```

### Table of Contents

[Basic Docker CLIs](#0)

[Container Management CLIs](#1)

[Inspecting the Container](#2)

[Inspecting with Container](#3)

[Image Management Commands](#4)

[Image Transfer Commands](#5)

[Builder Main Commands](#6)

[The Docker CLI](#7)

[Docker Security(Scout,SBOM)](#8)

[Contributors](#9)

[Support and Community](#10)

[References](#11)

<a id='0'> </a>

### Basic Docker CLIs

|   Command    |           Description            |
| :----------: | :------------------------------: |
|  docker run  | Run a command in a new container |
| docker build |  Build an image from a Dockfile  |
| docker push  |    Push an image to registry     |
| docker pull  |  Pull an image from a registry   |
| docker stop  |     Stop a running container     |
|  docker rm   |  Remove one or more containers   |

 

