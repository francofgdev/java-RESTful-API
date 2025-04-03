<h1 align="center">Bradesco Java Cloud Native 2025</h1>

<p align="center">
  <img width="300" height="100" src="https://static.wixstatic.com/media/7a378f_5140deabd7d040378d740069cb692b87~mv2.png/v1/crop/x_0,y_10,w_1334,h_493/fill/w_568,h_208,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/logo%20DIO.png">
</p>

## Descrição 
<p align="justify">
Java RESTful API criada para o Bradesco Java Cloud Native.

## Diagrama de Classes

```mermaid

classDiagram
    class User {
        - name: string
        + getAccount(): Account
        + getFeatures(): Feature[]
        + getCard(): Card
        + getNews(): News[]
    }

    class Account {
        - number: string
        - agency: string
        - balance: float
        - limit: float
    }

    class Feature {
        - icon: string
        - description: string
    }

    class Card {
        - number: string
        - limit: float
    }

    class News {
        - icon: string
        - description: string
    }

    User "1" -- "1" Account : has
    User "1" -- "*" Feature : has
    User "1" -- "1" Card : has
    User "1" -- "*" News : has
```

## Ferramentas e tecnologias
![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)
![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)
![Java](https://img.shields.io/badge/Java-000?style=for-the-badge&logo=openjdk&logoColor=ED8B00)

## Ambiente de Desenvolvimento
Este projeto foi desenvolvido e testado nas seguintes condições:

* Versão Java: [Java 17.0.4.]
* IDE: [VSCode] 
* Sistema Operacional: [Windows 11] 
