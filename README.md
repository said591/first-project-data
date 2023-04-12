# Projet Python: Découverte Data Engineering

# Description

Ce projet est un projet de découverte de data engineering. Il a pour but de mettre en place un pipeline de traitement de données.

Nous chargeons un fichier CSV qui contient des utilisateurs et leurs informations. Nous alons ensuite le traiter pour en extraire des informations, puis les stocker dans une base de données. 

# Prérequis 
 
- Python 3.7
- Docker 
- Docker compose 
  

## Installation 

- Cloner le projet 
- créer un environnement virtuel 

    ````Bash
    # Linux
    python -m venv .venv

     # Windows
    py -m venv .venv
    ```` 
- Activer l'environnement virtuel
    ```bash
    # Linux
    .venv/bin/activate
    # Windows (batch/cmd)
    .venv/Scripts/activate.bat
    # Windows (powershell)
    .venv/Scripts/Activate.ps1
    ```
- Installer les dépendances
    ```bash
    pip install -r requirements.txt
    ```

![ open classroom ] (https://user.oc-static.com/upload/2021/09/06/1630929646554_Fiche%20-%20Linux.png)