Nous avons 3 jours ensemble pour apprendre à faire des jeux dont les périphériques (input) sont non classique.

Mon but est de vous partager les connaissances que j'ai accumlé ces derniers années sur le sujet.


List temporaire:
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
 
Mention honorable:
- Infrarouge
- Xbox Live
- Playstation Remote
  
   

 
