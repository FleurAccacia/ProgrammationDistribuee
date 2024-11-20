# *Exercice de Programmation Distribuée*

Fait par : 

-AKAVI Marco-Florent

-NAMADOU Rasika

-Gracia GOKAR

## Comparaison (Avantages et inconvénients ) TCP/IP & UDP

### Introduction

   Les protocoles TCP/IP et UDP constituent les fondements de la communication sur les réseaux informatiques. Bien qu'ils partagent l'objectif commjun de transmettre des données, ils adoptent des approches fondamentalement différentes en termes de fiabilité, de performance et d'utilisation des ressources.



###  . Avantages et inconvénients TCP/IP (Transmission Control Protocol/Internet Protocol)

   Le protocole TCP/IP assure une transmission de données fiable, ordonnée et sans perte. Il établit une connexion virtuelle entre l'émetteur et le récepteur, ce qui permet de garantir la livraison de tous les segments de données. TCP/IP implémente des mécanismes de contrôle de flux et de congestion pour optimiser l'utilisation du réseau.

> ***Avantages***
- **Fiabilité :** TCP/IP garantit que les données soient transmises dans l'ordre et sans erreurs. Il retransmet les paquets perdus ou corrompus, assurant ainsi une livraison fiable et complète.
+ **Contrôle de flux :** TCP/IP ajuste le débit des données en fonction de la capacité du réseau et régule la transmission , évitant ainsi la congestion.
* **Connexion orientée :** TCP/IP établit une connexion stable entre l'émetteur et le récepteur avant de transmettre les données.
- Idéal pour Les applications nécessitant une haute fiabilité, comme le transfert de fichiers, le courrier électronique, le streaming vidéo de haute qualité et les applications de VoIP.

> ***Inconvénients***
+ **Complexité :** TCP est un protocole dont le processus de connexion et de vérification est plus complexe que UDP, ce qui peut entraîner une surcharge de traitement.
* Temps de configuration plus long
- **Latence :** La fiabilité et le contrôle de flux de TCP peuvent introduire une latence plus élevée, ce qui peut être problématique pour les applications en temps réel.
+ **Overhead plus important :** TCP nécessite plus de ressources et bande passante.


###  . Avantages et inconvénients UDP (User Datagram Protocol)

Le protocole UDP offre un service de datagrammes sans connexion, ce qui signifie qu'il n'y a pas d'établissement de connexion préalable. Les datagrammes UDP sont transmis individuellement, sans garantie de livraison ni d'ordre d'arrivée.

> ***Avantages***
* **Vitesse :** UDP effectue une transmission rapide sans mécanismes complexes de contrôle.
- **Légèreté :** UDP est un protocole léger, ce qui le rend idéal pour les applications à faible bande passante et rend la communication plus directe.
+ Idéal pour Les applications en temps réel telles que les jeux vidéo en ligne, la vidéoconférence, la diffusion en direct, les applications de chat et les protocoles de découverte de réseau.
* **Overhead minimal :** Utilisation de moins de ressources système.

> ***Incovénients***
