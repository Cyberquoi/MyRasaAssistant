# MyRasaAssistant
Agent conversationnel s'appuyant sur RasaPro

# Installation

## Créer le projet 
git clone https://github.com/Cyberquoi/MyRasaAssistant.git

## Paramétrer le gitignore
.env


## créer l'environnement virtuel et ajouter les librairie (Rasa supports Python 3.10 and 3.11)
python.exe -m pip install --upgrade pip
pip install rasa-pro

## créer le fichier .env
RASA_PRO_LICENSE=sxxJhbGciOiJSUzI1NiIsIxxxx
RASA_PRO_BETA_STUB_CUSTOM_ACTION=true

# Exécution

## Démarrer le projet
source .env

## Commandes Rasa
- rasa train
- rasa inspect
- rasa actions
