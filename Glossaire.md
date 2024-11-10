![Anycast](https://github.com/user-attachments/assets/e0d44b96-5a94-493c-8ee1-d275040be10e)
==========================================================================================================================================================================
### A
### B
##### **.Bridge :** Permettent de relier des réseaux physiques différent(couche 2)
### C
##### **.Cable :**
##### - droites (MDI) entres sur les hôtes (ordinateurs)
##### - croisées (MDI-X) les équipements d'interconnexion (hub & switch)
![image](https://d33wubrfki0l68.cloudfront.net/ee57ecfdbb103618889aa78e27185be81de8284e/57ebf/assets/images/ccna/lucidchart/acf26363-1a71-4848-9f1b-0a4e4d624d35.png)
![image](https://www.xeilom.fr/Files/126457/Img/03/cat8-web-7.png)
##### **.Connecteurs  :**
![image](https://d33wubrfki0l68.cloudfront.net/beb8f97df171fb9456b945f3c8497663439f784e/b5018/assets/images/ccna/connecteurs_fo.jpg)

### D
##### **.Datagramme** :Un datagramme est un paquet de données transmis avec ses adresses de source et de destination par un réseau de télécommunications (WAN) ou un réseau local (LAN)
### E
##### **.Encapsulation :** En programmation, l’encapsulation désigne le regroupement de données avec un ensemble de routines qui en permettent la lecture et la manipulation. Ce principe est souvent accompagné du masquage de ces données brutes1 afin de s’assurer que l’utilisateur ne contourne pas l’interface qui lui est destinée. L’ensemble se considère alors comme une boîte noire ayant un comportement et des propriétés spécifiés
##### **.EtherType :** Ce champ de 2 octets a été défini dans le standard Ethernet II pour indiquer le type de protocole de niveau 3 employé pour transmettre le message.
##### **. :**
##### **. :**
### F
##### **. :**
### G
##### **.Gateway :** Point du réseau qui fonctionne comme une entrée vers un autre réseau (VLAN) différent.(couche 4)
### H
##### ##### **.Hôte :** Noeud qui 'est pas un routeur
##### **.Hub :** ConcentrationLes équipements
##### Le concentrateur (hub) Concentre le trafic réseau provenant de plusieurs hôtes. Recopie les données reçues sur un port sur tous les autres ports.(couche 1)
### I
##### **.IPv4 :** (Internet Protocol version 4) est la première version d'Internet Protocol (IP) à avoir été largement déployée, et qui forme encore en 2024 la base de la majorité des communications sur Internet, par rapport à l'IPv6.
##### Notation IPv4:
![image](https://upload.wikimedia.org/wikipedia/commons/6/66/IPv4_address_structure_and_writing_systems-en.svg)
##### Entête IPv4:
![image](https://d33wubrfki0l68.cloudfront.net/dc84ba071e2f7c54abf89895b3c01ccb258faf2d/0bc12/assets/images/ccna/lucidchart/e3e153b3-d2f9-480a-82d4-e8f953519b1f.png)
### J
### K
### L
##### **.LAN :** Un réseau local, en anglais Local Area Network ou LAN, est un réseau informatique où les terminaux qui y participent (ordinateurs, etc.)
##### **.Liens :** Porocoles sous IP( Ethernet, WIFI,ATM)
### M
##### **.MAC header :(trame ethernet)** Suite de 14 octets, (6 destinataire + 6emetteur + 2 EtherType ), L'adresse source est toujours celle d'une interface unique (unicast). La destination peut être une adresse unique, de groupe (multicast) ou de diffusion générale (broadcast = FF-FF-FF-FF-FF-FF)
##### **.Masque de sous réseau :** Un masque de sous-réseau (désigné par subnet mask, netmask ou address mask en anglais) est un masque distinguant les bits d'une adresse IPv4 utilisés pour identifier le sous-réseau de ceux utilisés pour identifier l'hôte.

##### **.MTU (et fragmentation)  :** Chaque réseau/routeur/ordinateur/... a une taille de paquet maximale qu'il accepte et/ou peut gérer : le Maximum Transmission Unit (unité de transmission maximale), ou MTU.Pour la fragmentation ce que fait le routeur : il découpe le paquet en plusieurs mini-paquets compatibles avec le MTU de l'équipement, qui sont envoyés un par un. Les mini-paquets créés par le routeur sont appelés des fragments. Notons que l'en-tête du paquet IP originel est recopié au début de chaque fragment, sans quoi ceux-ci ne pourraient pas être routés correctement. De plus, les fragments sont envoyés uns par uns par le routeur, si possible dans l'ordre.
##### **.Le modèle OSI :** (de l'anglais Open Systems Interconnection) est une norme de communication de tous les systèmes informatiques en réseau. C'est un modèle de communications entre ordinateurs proposé par l'ISO (Organisation internationale de normalisation) qui décrit les fonctionnalités nécessaires à la communication et l'organisation de ces fonctions.
##### **Les différentes couches** :
   * ##### Couche 1: Physique (PDU: bit) Définie l’interface, les connecteurs, le câblage.
   * ##### Couche 2: Liaison (PDU: trame) Gère les méthodes d’accès au média, gère le contrôle d’erreurs.
   * ##### Couche 3: Réseau (PDU: paquet) Assure le routage et l’interconnexion de réseaux hétérogènes.
   * ##### Couche 4: Transport (PDU: segment ou datagramme) Responsable du transfert de bout en bout des informations (découpage des données, contrôle de flux, réordonnancement).
   * ##### Couche 5: Session (PDU: données)Assure l’ouverture et la fermeture du dialogue entre les ordinateurs, la reprise après coupure et la sécurité. 
   * ##### Couche 6: Présentation (PDU: données) Chargée de la syntaxe et du format des données.
   * ##### Couche 7: Application (PDU: données applicatives) Définie le type ou la signification des informations à échanger.
### N
##### **.Noeud :** Equipement supportant l'IP.
### O
### P
##### **.préambule :(trame ethernet)** Permet la synchronisation des équipements, il est une suite de 0 et de 1 alternés. Il permet à l'horloge du récepteur de se synchroniser sur celle de l'émetteur.
##### **.Payload ou (trame ethernet) (donnée transportée) :(trame ethernet)**: Les données sont directement transmises au niveau réseau identifié par l'Ethertype.Longeur mini/max : 46 octets/1500 octets 
##### **.Plan d'adressage:** lors de la création d'un réseau d’entreprise IP, ce réseau interconnectant différents sites et réseaux on réalise un plan d’adressage. Cette opération a pour but de définir pour chaque réseau physique (LAN et WAN) une adresse de réseau IP. Pour chaque machine de chacun de ces réseaux.
##### **.Protocoles**:  
   * ##### **.ARP :** L’Address Resolution Protocol (ARP, protocole de résolution d’adresse) est un protocole utilisé pour associer l'adresse de protocole de couche réseau (typiquement une adresse IPv4) d'un hôte distant, à son adresse de protocole de couche de liaison (typiquement une adresse MAC). Il se situe à l’interface entre la couche réseau (couche 3 du modèle OSI) et la couche de liaison (couche 2 du modèle OSI).
   * ##### **CSMA/CD** :(Carrier Sense Multiple Access with Collision Detection) cette méthode permet à une station d'écouter le support physique de liaison (câble ou fibre) pour déterminer si une autre station transmet une trame de données (niveau déterminé de tension électrique ou de lumière). Si tel n'est pas le cas (donc s'il n'y a pas eu de signal), elle suppose qu'elle peut émettre
  
  * ##### **.ICMP :** Internet Control Message Protocol (ICMP, Protocole de message de contrôle sur Internet) est l’un des protocoles fondamentaux constituant la suite des protocoles Internet. C'est un protocole de couche réseau (couche no 3 du modèle OSI), au même niveau que le protocole Internet (IP). Le protocole IP ne gérant que le transport des paquets et ne permettant pas l'envoi de messages d'erreur, on lui associe ICMP pour contrôler les erreurs de transmission

   * #####  **HTTP** (Hypertext Transfer Protocol) port 80 ⇒ Protocole de communication du web
   * ##### **FTP** (File Transfer Protocol) port 21 ⇒ Définition des envois de fichiers sur un réseau.
   * ##### **PDU** (Protocol Data Unit) ⇒  est l'unité de mesure des informations échangées dans un réseau informatique. 
   * #####  **SMTP** (Simple Mail Transfer Protocol) port 25 ⇒ Sert à envoyer les e-mails.
### Q
### R
##### **.Répéteur :** Equipement simple permettant d'amplifier un signal(couche 1)
##### **.Routage:** Le routage est le mécanisme par lequel des chemins sont sélectionnés dans un réseau pour acheminer les données d'un expéditeur jusqu'à un ou plusieurs destinataires
##### **.Routeur :** Un routeur est un équipement réseau informatique assurant le routage des paquets. Son rôle est de faire transiter des paquets d'une interface réseau vers une autre, au mieux, selon un ensemble de règles. (couche 3)
### S
##### **.Switch :** Un switch désigne un commutateur réseau, équipement ou appareil qui permet l'interconnexion d'appareils communicants, terminaux, ordinateurs, serveurs, périphériques reliés à un même réseau physique.
### T
##### **.TCP/IP :** désigne communément une architecture réseau, mais cet acronyme désigne en fait 2 protocoles étroitement liés : un protocole de transport, TCP (Transmission Control Protocol) qu’on utilise « par-dessus » un protocole réseau, IP.
### U
### V 
##### **.VLAN :** ils permettent : 
* #####  de séparer les flux de données.
* #####  de segmenter le réseau : réduire la taille d'un domaine de collision .
* #####  d'améliorer la sécurité : permet de créer un ensemble logique isolé pour améliorer la sécurité. Le seul moyen pour communiquer entre des machines appartenant à des VLAN différents est alors de passer par un routeur.
* #####  Par conséquent, les VLAN permettent aussi d'améliorer la gestion du réseau et d'optimiser la bande passante.
### W
##### **.WAN :** Un réseau étendu1, souvent désigné par son acronyme anglais WAN (wide area network), est un réseau informatique ou un réseau de télécommunications couvrant une grande zone géographique, typiquement à l'échelle d'un pays, d'un continent, ou de la planète entière
### X
### Y
### Z


##### **. :**
![image]()
























![Uploading <?xml version="1.0" encoding="UTF-8" standalone="no"?>
<!-- Created with Inkscape (http://www.inkscape.org/) -->
<svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://web.resource.org/cc/"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:sodipodi="http://inkscape.sourceforge.net/DTD/sodipodi-0.dtd"
   xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
   version="1.0"
   width="900pt"
   height="600pt"
   id="svg2"
   sodipodi:version="0.32"
   inkscape:version="0.43"
   sodipodi:docname="anycast.svg"
   sodipodi:docbase="/home/cyberix/Desktop">
  <metadata
     id="metadata28">
    <rdf:RDF>
      <cc:Work
         rdf:about="">
        <dc:format>image/svg+xml</dc:format>
        <dc:type
           rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
      </cc:Work>
    </rdf:RDF>
  </metadata>
  <sodipodi:namedview
     inkscape:window-height="555"
     inkscape:window-width="822"
     inkscape:pageshadow="2"
     inkscape:pageopacity="0.0"
     borderopacity="1.0"
     bordercolor="#666666"
     pagecolor="#ffffff"
     id="base"
     inkscape:zoom="0.50133333"
     inkscape:cx="562.5"
     inkscape:cy="375"
     inkscape:window-x="140"
     inkscape:window-y="63"
     inkscape:current-layer="svg2" />
  <defs
     id="defs4">
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow2Lend">
      <path
         d="M 8.7185878,4.0337352 L -2.2072895,0.016013256 L 8.7185884,-4.0017078 C 6.97309,-1.6296469 6.9831476,1.6157441 8.7185878,4.0337352 z "
         transform="matrix(-1.1,0,0,-1.1,5.5,0)"
         style="font-size:12px;fill-rule:evenodd;stroke-width:0.625;stroke-linejoin:round"
         id="path3334" />
    </marker>
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow1Mstart">
      <path
         d="M 0,0 L 5,-5 L -12.5,0 L 5,5 L 0,0 z "
         transform="scale(0.4,0.4)"
         style="fill-rule:evenodd;stroke:#000000;stroke-width:1pt;marker-start:none"
         id="path3349" />
    </marker>
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow1Lstart">
      <path
         d="M 0,0 L 5,-5 L -12.5,0 L 5,5 L 0,0 z "
         transform="scale(0.8,0.8)"
         style="fill-rule:evenodd;stroke:#000000;stroke-width:1pt;marker-start:none"
         id="path3355" />
    </marker>
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow2Mend">
      <path
         d="M 8.7185878,4.0337352 L -2.2072895,0.016013256 L 8.7185884,-4.0017078 C 6.97309,-1.6296469 6.9831476,1.6157441 8.7185878,4.0337352 z "
         transform="matrix(-0.6,0,0,-0.6,3,0)"
         style="font-size:12px;fill-rule:evenodd;stroke-width:0.625;stroke-linejoin:round"
         id="path3328" />
    </marker>
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow1Mend">
      <path
         d="M 0,0 L 5,-5 L -12.5,0 L 5,5 L 0,0 z "
         transform="scale(-0.4,-0.4)"
         style="fill-rule:evenodd;stroke:#000000;stroke-width:1pt;marker-start:none"
         id="path3346" />
    </marker>
    <marker
       refX="0"
       refY="0"
       orient="auto"
       style="overflow:visible"
       id="Arrow1Lend">
      <path
         d="M 0,0 L 5,-5 L -12.5,0 L 5,5 L 0,0 z "
         transform="scale(-0.8,-0.8)"
         style="fill-rule:evenodd;stroke:#000000;stroke-width:1pt;marker-start:none"
         id="path3352" />
    </marker>
  </defs>
  <g
     id="layer1">
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,-43.229,103.543)"
       style="opacity:1;fill:#ff5555;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4417" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,771.171,69.494)"
       style="opacity:1;fill:#ffff33;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4419" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,365.456,-118.582)"
       style="fill:#ffff33;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4421" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,336.885,384.275)"
       style="opacity:1;fill:#55ff55;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4423" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,636.885,-75.725)"
       style="opacity:1;fill:#55ff55;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4425" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,551.171,189.989)"
       style="opacity:1;fill:#ffff33;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4427" />
    <path
       d="M 305.71429 262.36218 A 54.285713 52.857143 0 1 1  197.14286,262.36218 A 54.285713 52.857143 0 1 1  305.71429 262.36218 z"
       transform="matrix(0.846481,0,0,0.874332,648.314,361.418)"
       style="opacity:1;fill:#55ff55;fill-opacity:1;stroke:#000000;stroke-width:8.80000019;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4429" />
    <path
       d="M 349.66498,331.66359 L 649.81391,231.70614"
       style="fill:none;fill-opacity:0.75;fill-rule:evenodd;stroke:#000000;stroke-width:4.69999981;stroke-linecap:butt;stroke-linejoin:miter;marker-start:none;marker-end:url(#Arrow2Lend);stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4433"
       sodipodi:nodetypes="cc" />
    <path
       d="M 352.45304,331.54914 L 428.61261,427.52255"
       style="fill:none;fill-opacity:0.75;fill-rule:evenodd;stroke:#000000;stroke-width:4.69999981;stroke-linecap:butt;stroke-linejoin:miter;marker-start:none;marker-end:url(#Arrow2Lend);stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4435"
       sodipodi:nodetypes="cc" />
    <path
       d="M 350.36306,333.94609 L 820.7354,573.8929"
       style="fill:none;fill-opacity:0.75;fill-rule:evenodd;stroke:#000000;stroke-width:4.69999981;stroke-linecap:butt;stroke-linejoin:miter;marker-start:none;marker-end:url(#Arrow2Lend);stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
       id="path4437"
       sodipodi:nodetypes="cc" />
  </g>
  <path
     style="fill:none;fill-opacity:0.75;fill-rule:evenodd;stroke:#000000;stroke-width:4.69999981;stroke-linecap:butt;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
     d="M 217.42021,334.10904 L 353.05851,332.11436"
     id="path1410" />
</svg>
Anycast.svg…]()



