

Nous avons 3 jours ensemble pour apprendre à faire des jeux dont les périphériques (input) sont non classique.

Mon but est de vous partager les connaissances que j'ai accumlé ces derniers années sur le sujet.

Dans cette exercice nous allons jouer à World of Warcraft:
- Mais le clavier est interdit !!!
- Les manettes sont tolérée dans un premeir temps mais interdit dans l'exercice final.

L'objectif ?
- Arriver à finir les mortes mines de Warcraft sans clavier et sans manettes achetetées sur le marcher( pas d'xbox, pas de ps et pas de manette VR)


List temporaire pour de la lecture:
- UART et Arduino Uno
  - Avantage, ça marche c'est rapide et la bonne manière de faire
  - Désavantage, faut être coder et avoir une app lisant le SerialPort  
- Simuler un touche avec Arduino Mega et Micro
  - Avantage, c'est simple
  - Ca marche sur tout les platformes à clavier
  - Désavantage, faut que votre jeu soit en focus par Window
- Envoyé une note de musique avec du MIDI
  - Avantage,
    - vous pouvez nommer vos devices :)
    - Message de 3 bytes, très rapide
  - Ddésavntage, il faut avoir un code quand Unity3D qui arrive à lire le MIDI
- HID avec un Raspberry Pi Pico
  - Avantage, c'est compatible avec tout les appareils
  - Désavantage, Faut créé des rapports de HID ce qui est pas intuitif
- Generic Arcade button
  - Avantage, rien à configurer
  - Désavantage, Seulement des bouttons via touches
- Simuler un manette XInput avec Arduino
  - Fonction avec tout les jeux à manette
- Simuler un manette XInput avec Arduino et Brook
  - Avantage ça marche pour les consoles
- Utiliser un micro:bit  https://amzn.to/3Ur9ne2
- Utiliser un Makey Makey: https://amzn.to/4hpktdI
- Utiliser un RP2040: RP2040: https://amzn.to/3NGOrfr
- Utiliser un RP2040 Watch: https://amzn.to/3NGOrfr
- CapacitiveController en Arduino
  - (Guide:https://www.instructables.com/3-Alternative-to-Makey-Makey/)
- HC06 via UART
  - Avantage, pas besoin de réseaux
  - Désavantage,
    - savoir les configurerr
    - Le bluetooth sans perte, c'est lent.
- BLE
  - Avantege, plus standardiser et consome moin
  - Désavnatge, C'est de librarie différente du Bluetooth classique
- UDP via Raspberry Pi et autre
  -  Avantage, permet de broadcaster sur un ip et port sans devoir faire un lien
  -  Désavantage,
    - pas de communication pour savoir si tout se passe bien
    - Comme pour le TCP, il y a des ports et des écuritées qui bloque les messages.
    - Ne tourne pas dans les navigateurs
  - changer l'address IP de la cible
- TCP via un micro ordinateur
  - Avantage, il y a une communication et l'on est certain que le message est envoyé
  - Désavantage,
    - gérer les déconnections
    - changer l'address IP de la cible 
- OSC via un micro ordinateur
  -  Avantage, livrary de son très connue et intégrable en Unity3D et autres engines
  -  Désavantage, c'est un librarie de music qu'il faut ajouter au project
- WebPage depuis un Raspberry Pi Pico Wifi
  - Avantage, L'address en change pas
  - Désavantage,
    - c'est lente. Très lente.
    - Il faut un siteweb avec un base de donnée  
- WebSocket depuis un Raspberry Pi ou Pi Pico
  - Avantage, plus rapide d'un pageweb
  - Désavantage,
    - Il faut u microcontroller ou appareil qui support le websocket
- MQTT depuis un micro ordinateur
  - Avantage, un server standardiser avec un mot de passe très utiliser par l'industrie
  - Désavantage,
    - après le mots de passe, il y a une gestion de compte infamme
    - Il faut héberger un serveur qui peut devenir couteux.
- Mirror
  - Avantage, ils ont 8 methodes de transport des données :)
  - Désavantage, il ne gère pas l'hébergement
- Photon
  - Avantage, il gère l'hébergement :)
  - Désavantage, c'est chère
- Utiliser des antennes FM pour Arduino
- Utiliser des channel FM de drone (SkyDive)
- Utiliser des inputs Virtuel avec VRTK et Unity Tookkit sur Quest3s
  - Utiliser les mains
  - Utiliser le gaze du casque
  - Utiliser le regard (Pico) 
- Utiliser l'AR avec Vuforia et AR Core
- Utiliser le Leap Motion pour les mains
- Utiliser un vieux Quest pour les mains
- Utiliser le son d'un microphone
- Utiliser le son d'un jeu
- Utiliser le pixel d'un écran
- Utiliser le son d'un micro arduino
- Utiliser le variation d'un spectrogramme

 
Mention honorable:
- Infrarouge sur Arduino
- Xbox Live et XInput pour simuler 4 manettes de jeux
- Playstation Remote pour 
- Injection de command line avec un raspberry micro
- Utilisation de 2040 watch pour le gryo
- Conductive PLA https://amzn.to/40kPl95
- Conductive Paint https://amzn.to/40maOP0
- vJoy pour simuler des manettes
- Hack un jouet existant pour la fonction FM
  - Acheter un jouet FM à <10€


Sujet: 
- Kit de senseurs pour Arduino

Resistor:
- Pack 200 https://amzn.to/3NHXQDy
- 
   
Complexe:
- esp32

To do:
- scratch variable injection via TamperMonkey et Websocket.
 
