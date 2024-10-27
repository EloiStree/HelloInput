

Nous avons trois jours ensemble pour apprendre à créer des jeux avec des périphériques d'entrée non conventionnels.

Mon objectif est de vous transmettre les connaissances que j'ai accumulées au fil des années sur ce sujet.

Dans cet exercice, nous allons jouer à *World of Warcraft* :
- **Mais le clavier est interdit !**
- Les manettes sont tolérées dans un premier temps, mais seront interdites pour l'exercice final.

**Objectif :**  
Terminer les Mortes Mines dans *World of Warcraft* sans clavier ni manettes achetées dans le commerce (pas de manette Xbox, PS, ou VR).

**Liste temporaire de lecture :**

- **UART et Arduino Uno**
  - Avantages : rapide et efficace, méthode recommandée.
  - Inconvénients : nécessite de coder et d'avoir une application qui lit le port série.

- **Simulation de touches avec Arduino Mega et Micro**
  - Avantages : simple et fonctionne sur toutes les plateformes avec clavier.
  - Inconvénients : le jeu doit être en focus dans Windows.

- **Envoi de notes musicales via MIDI**
  - Avantages :
    - Possibilité de nommer les appareils.
    - Messages de trois octets, très rapides.
  - Inconvénients : nécessite du code dans Unity3D pour lire le MIDI.

- **HID avec un Raspberry Pi Pico**
  - Avantages : compatible avec tous les appareils.
  - Inconvénients : nécessite de créer des rapports HID, ce qui peut être complexe.

- **Boutons d’arcade génériques**
  - Avantages : aucune configuration requise.
  - Inconvénients : limitation aux boutons via des touches.

- **Simulation de manette XInput avec Arduino**
  - Fonctionne avec tous les jeux compatibles manette.

- **Simulation de manette XInput avec Arduino et Brook**
  - Avantages : compatible avec les consoles.

- **Utilisation de micro:bit**
  - [Lien pour achat](https://amzn.to/3Ur9ne2)

- **Utilisation de Makey Makey**
  - [Lien pour achat](https://amzn.to/4hpktdI)

- **Utilisation d'un RP2040 et d'une montre RP2040**
  - [Lien pour achat](https://amzn.to/3NGOrfr)

- **Capacitive Controller en Arduino**
  - [Guide](https://www.instructables.com/3-Alternative-to-Makey-Makey/)

- **HC06 via UART**
  - Avantages : pas besoin de réseau.
  - Inconvénients :
    - Nécessite des configurations.
    - Le Bluetooth sans perte est lent.

- **BLE**
  - Avantages : plus standardisé, consomme moins.
  - Inconvénients : différentes bibliothèques du Bluetooth classique.

- **UDP via Raspberry Pi et autres**
  - Avantages : diffusion sur une IP et un port sans connexion directe.
  - Inconvénients :
    - Pas de retour de communication pour vérifier le bon fonctionnement.
    - Nécessite la gestion de ports et de sécurités qui bloquent parfois les messages.
    - Ne fonctionne pas dans les navigateurs.
    - Demande de configurer l’adresse IP cible.

- **TCP via un micro-ordinateur**
  - Avantages : communication bidirectionnelle, garantie d’envoi des messages.
  - Inconvénients :
    - Gestion des déconnexions.
    - Changement de l’adresse IP cible nécessaire.

- **OSC via un micro-ordinateur**
  - Avantages : bibliothèque sonore bien connue, intégrable dans Unity3D et autres moteurs.
  - Inconvénients : nécessite une bibliothèque musicale à ajouter au projet.

- **Page Web via un Raspberry Pi Pico Wifi**
  - Avantages : l’adresse reste fixe.
  - Inconvénients :
    - Très lente.
    - Nécessite un site web avec une base de données.

- **WebSocket via Raspberry Pi ou Pi Pico**
  - Avantages : plus rapide qu’une page Web.
  - Inconvénients :
    - Nécessite un microcontrôleur ou un appareil compatible WebSocket.

- **MQTT via un micro-ordinateur**
  - Avantages : serveur standardisé avec mot de passe, largement utilisé en industrie.
  - Inconvénients :
    - Gestion de comptes complexe.
    - Hébergement de serveur coûteux.

- **Mirror**
  - Avantages : huit méthodes de transport de données.
  - Inconvénients : ne gère pas l’hébergement.

- **Photon**
  - Avantages : gestion de l’hébergement.
  - Inconvénients : coûteux.

- **Utilisation d’antennes FM pour Arduino**
- **Utilisation de canaux FM de drones (SkyDive)**
- **Inputs virtuels avec VRTK et Unity Toolkit sur Quest3**
  - Utilisation des mains.
  - Utilisation du gaze du casque.
  - Utilisation du suivi du regard (Pico).

- **Utilisation de l’AR avec Vuforia et AR Core**
- **Utilisation de Leap Motion pour les mains**
- **Utilisation d’un ancien Quest pour le suivi des mains**
- **Utilisation de l’entrée audio d’un microphone**
- **Utilisation des variations de spectrogrammes audio**
  
**Mentions honorables :**
- Infrarouge sur Arduino.
- Xbox Live et XInput pour simuler quatre manettes de jeux.
- Remote PlayStation Remote.
- Injection de commandes en ligne via un Raspberry micro.
- Utilisation de la montre RP2040 pour le gyroscope.
- Conductive PLA – [Lien pour achat](https://amzn.to/40kPl95).
- Peinture conductrice – [Lien pour achat](https://amzn.to/40maOP0).
- vJoy pour simuler des manettes.
- Modifier un jouet FM pour ajouter des fonctionnalités pour moins de 10€.
- Use Raspberry Pi Zero as relay of a keyboard to make it become a macro board

**Sujet :**
- Kits de capteurs pour Arduino.

**Résistances :**
- Pack de 200 résistances – [Lien pour achat](https://amzn.to/3NHXQDy).

**Complexe :**
- ESP32.

**À faire :**
- Injection de variables dans Scratch via TamperMonkey et WebSocket.
