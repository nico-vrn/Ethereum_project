# Ethereum Web3.js Project
Ce projet est un exemple d'application Web qui utilise la bibliothèque Web3.js pour interagir avec la blockchain Ethereum via un navigateur Web.

## Fonctionnalités
Le projet offre deux fonctionnalités principales :

1. Sending Ethereum to an address : L'utilisateur peut envoyer de l'ETH à une adresse Ethereum spécifiée en cliquant sur le bouton "sendEthButton". Cette fonctionnalité utilise la méthode "eth_sendTransaction" de l'objet "ethereum" pour envoyer une transaction avec les paramètres suivants :
* `from`: le compte Ethereum de l'utilisateur
* `to`: l'adresse Ethereum du destinataire
* `value`: la quantité d'ETH à envoyer, en Wei (1 ETH = 10^18 Wei)
* `gasPrice`: le prix du gas pour la transaction, en Wei par unité de gas
* `gas`: la quantité maximale de gas à utiliser pour la transaction

2. Getting Ethereum account : L'utilisateur peut obtenir son compte Ethereum en cliquant sur le bouton "enableEthereumButton". Cette fonctionnalité utilise la méthode "eth_requestAccounts" de l'objet "ethereum" pour demander au navigateur l'autorisation d'accéder à un compte Ethereum. Si l'utilisateur accepte l'autorisation, la variable "accounts" est mise à jour avec le compte Ethereum de l'utilisateur.

## Prérequis
Pour exécuter ce projet, vous devez disposer des éléments suivants :

* Un navigateur Web prenant en charge la spécification Web3 (par exemple, Google Chrome avec l'extension [Metamask](https://metamask.io/) installée)
* Une adresse Ethereum avec des fonds pour effectuer des transactions

## Installation
1. Clonez ce dépôt de code sur votre machine locale :

```sh
git clone https://github.com/votre-utilisateur/ethereum-web3js-project.git
```

2. Ouvrez le fichier index.html dans un navigateur Web.

## Configuration
Aucune configuration n'est requise pour ce projet.

## Utilisation
1. Cliquez sur le bouton `enableEthereumButton` pour autoriser le navigateur à accéder à votre compte Ethereum.

2. Cliquez sur le bouton `sendEthButton` pour envoyer de l'ETH à une adresse Ethereum spécifiée.

## Ressources supplémentaires
* [Documentation Web3.js](https://web3js.readthedocs.io/en/v1.8.2/)
* [Documentation Ethereum](https://ethereum.org/fr/developers/)

## Auteur
Ce projet a été créé par Lefranc Nicolas en 2021.
