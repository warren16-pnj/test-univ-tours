# test-univ-tours



Projet test pour montrer l'utilisation

&nbsp;	ce que le projet va permettre : 

&nbsp;	- Récuperer des messages

&nbsp;	- les stocker en BDD

&nbsp;	- les affihcer

&nbsp;	- utiliser node-RED

![image](images.jpg)

```mermaid
flowchart TD
    mosquitto[Serveur<br>mosquitto] --> |messages| RPi[raspberry Pi<br>Node-RED<br> Documentation]
    RPi --> BDD
    RPi --> GitHub
```
```mermaid
flowchart TD
    github --> |git clone URL| local
    github --> |git pull main| local
    local -->| git add file 1 file 2 | index
    index --> | git add nom du fichier| local
    local --> |edition/creation<br>fichier| local
```


