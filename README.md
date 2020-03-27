# HUB - Découverte Rasa

## Installation

#### **Pip et Python**

Assurez vous d'avoir python et pip sur votre ordinateur.

Pour cela, lancez la commande:

`$ pip`

Si la commande n'est pas reconnue, suivez les instructions d'installation de pip:

https://pip.pypa.io/en/stable/installing/

#### **Rasa**
Installez la dernière version de rasa:

`$ git clone https://github.com/RasaHQ/rasa.git`

`$ cd rasa`

`$ pip install -r requirements.txt`

`$ pip install -e .`

Installez la dernière version de rasa sdk:

`$ git clone https://github.com/RasaHQ/rasa-sdk.git`

`$ cd rasa-sdk`

`$ pip install -r requirements.txt`

`$ pip install -e .`

## Création, compilation et tests

#### **Création**

Créez un nouveau projet :

`$ rasa init`

#### **Compilation**

Pour compiler ou recompiler votre code, vous devez entrainer le reseau neuronal.

Lancez la commande:

`$ rasa train`

Vous pouvez obtenir une vue d'ensemble de votre modele:

`$ rasa visualize`

#### **Tests**

-lancez l'interface graphique sur navigateur (requert rasa x):

`$ rasa x`

-ou bien lancez un shell

`$ rasa shell`

Vous pourrez maintenant interragir avec le chatbot.

Si vous utilisez les actions, vous devez lancer un serveur dans un nouveau terminal :

`$ rasa run actions`

## Documentation

Installation Rasa : https://rasa.com/docs/rasa/user-guide/installation/

Tutoriels : https://rasa.com/docs/rasa/user-guide/rasa-tutorial/

Tuto slots : https://rasa.com/docs/rasa/core/slots/
