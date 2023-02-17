# Event-Driven-Architecture-avec-KAFKA-et-Spring-Cloud-Streams

## KAFKA :
### Apache Kafka est un projet à code source ouvert d'agent de messages développé par l'Apache Software Foundation et écrit en Scala. Le projet vise à fournir un système unifié, en temps réel à latence faible pour la manipulation de flux de données. Sa conception est fortement influencée par les journaux de transactions.

## Les étapes pour travailler avec KAFKA :
#### 1. Télécharger Kafka.
#### 2. Démarrer Zookeeper.
#### 3. Démarrer Kafka-server.
#### 4. Exécuter Zookeper et Kafka.
![q1](https://user-images.githubusercontent.com/75500068/219802262-5fcd1f45-233a-47b6-8269-4453e91a2db0.png)

![q2](https://user-images.githubusercontent.com/75500068/219801243-9915e17d-3f5e-45b5-b9e3-6bc5065567ec.png)

#### 5. Tests avec Kafka-console-producer et kafka-console-consumer avec la commande :
##### ./kafka-console-producer.sh --broker-list localhost:9092 --topic R1

#### 6. Création d'un Service Producer KAFKA via un Rest Controller.
![q6](https://user-images.githubusercontent.com/75500068/219801995-3047bb4c-0bb5-4e20-9bd7-57c2347b9dde.png)
![q3](https://user-images.githubusercontent.com/75500068/219802016-b1bdc913-7353-4dee-b3c0-8732e1d42ddb.png)
![q4](https://user-images.githubusercontent.com/75500068/219802029-414c8e60-7ff0-46b8-bf97-485ec7742b74.png)
![q5](https://user-images.githubusercontent.com/75500068/219802044-acc468c6-76ba-4532-9a13-5ae24082c9ee.png)
![q7](https://user-images.githubusercontent.com/75500068/219802061-43ba75e5-64e8-485f-85e0-4c8d9c56f77d.png)

#### 7.  Création d'un Service Consommateur KAFKA.
![q1](https://user-images.githubusercontent.com/75500068/219802612-18b0d383-6a83-4a69-9e18-555ad3dc4677.png)
![q2](https://user-images.githubusercontent.com/75500068/219802620-3c24415a-bbc7-4ece-a4a8-cb2cedfe4395.png)
![q3](https://user-images.githubusercontent.com/75500068/219802630-cc73a410-24fc-458d-9337-c0ca485de670.png)
![q4](https://user-images.githubusercontent.com/75500068/219802644-db272875-3f05-43e9-a74d-da4a94854d3a.png)

#### 8. Création d'un fournisseur de services KAFKA.
![q5](https://user-images.githubusercontent.com/75500068/219802992-dd22ae94-4aba-459a-af4d-fe4461ca491e.png)
![q6](https://user-images.githubusercontent.com/75500068/219803003-cf662298-07c3-4b3f-85a5-808ff65d5b47.png)
![q7](https://user-images.githubusercontent.com/75500068/219803012-e884c307-e09c-4aba-b749-34e2c153a283.png)
![q8](https://user-images.githubusercontent.com/75500068/219803030-e584a973-689f-4bf1-ae84-7669deec5500.png)

#### 9. Création d'un fournisseur de services KAFKA et d'un consommateur en même temps.
![q1](https://user-images.githubusercontent.com/75500068/219803425-d2520291-df57-48a4-af9a-98acfa8bd54f.png)
![q2](https://user-images.githubusercontent.com/75500068/219803443-5732cf93-4a6f-4878-a9c6-f397733ce11b.png)
![q3](https://user-images.githubusercontent.com/75500068/219803458-80152140-12af-4881-82c2-9fa0d3328d37.png)

#### 10. Création d'un service d'analyse de données de traitement de flux en temps réel avec Kaflka Streams.
![q4](https://user-images.githubusercontent.com/75500068/219803735-45034925-145c-4612-a8ad-7734414c110a.png)
![q5](https://user-images.githubusercontent.com/75500068/219803748-179e9a1a-536b-496e-ac6e-4a189d3b57bd.png)
![q6](https://user-images.githubusercontent.com/75500068/219803768-d2e5d20f-8c61-4ae5-aee1-d7473375c4a8.png)

#### 11. Création d'une application web qui affiche les résultats de Stream Data Analytics en temps réel
![q1](https://user-images.githubusercontent.com/75500068/219804227-27a84d75-33b1-47a4-b81a-1efb36384697.png)
![q2](https://user-images.githubusercontent.com/75500068/219804236-756b79fa-1bb9-4801-b45c-941484bf2629.png)
![q3](https://user-images.githubusercontent.com/75500068/219804250-b328ddb6-a438-4d38-9e16-23f5102ae3ca.png)
![q4](https://user-images.githubusercontent.com/75500068/219804263-3f19cc21-3f72-47a9-9e63-964867971f74.png)
![q5](https://user-images.githubusercontent.com/75500068/219804275-a1335c42-d0cb-486a-ad27-f9908559bae0.png)

