# Doppelgänger

## Idée
 "Doppelgänger" est une installation interactive qui a la forme d'un miroir qui déforme le reflet de l'utilisateur, projettant des distortions sonores et visuelles, symbolisant l’exploitation de la vie privée par des groupes qui cherchent à abuser nos données personnelles.
 <br>
 <br>
 Près de l'écran qui sert comme miroir, une caméra capture le visage de l'utilisateur pour lui appliquer des filtres à chaque différente visite; son reflet sera déformé pour simuler les conséquences de l'utilisation non consentie de nos informations personnelles. Des indices visuels et sonores apparaissent, suggérant que les traits de l’utilisateur sont "analysés" par une intelligence artificielle. Pour chaque visage unique détecté dans un cycle de 24 heures, un point apparaîtra sur un diagramme affiché sur un autre écran, illustrant le nombre de personnes capturées. Le but de l'installation est d'inviter les utilisateurs à une réflexion sur la collecte des données personnelles auxquelles on ne voudrait pas divulguer, en provoquant un sentiment d'inconfort qui poussera le monde à rester vigilant ainsi que de lutter contre les organismes qui abusent de notre droit à la vie privée.

## Scénario
```mermaid
graph TD;
A[Le visiteur se tient devant le miroir] --> B[Detection faciale activée]
    B --> C{Visage déjà détecté aujourd'hui?}
    C -- Non --> D[Le visage est analysé]
    D -- Après un peu de temps --> E[Le reflet commence à se distordre lentement et des bruits légers commencent à jouer]
    C -- Oui --> F[Le visage est déformé d'une nouvelle façon]
    
    E --> G{L'utilisateur fait des expressions?}
    F --> G
    G -- Oui --> H[Les distorsions augmentent]
    G -- Non --> I[Le reflet reste statique]

    H --> J[Des messages cryptiques superposés commencent à jouer]
    I --> K[Effets visuels et sonores glitchés passifs]
    
    J & K --> L{La personne reste ?}
    L -- Oui --> M[Les effets gardent une intensité constante]
    L -- Non --> N[Les effets sont réinitialisés en attente de la prochaine personne]

    N --> O[Affichage du nombre de visages capturés sur un autre écran à travers la journée]
    M --> O

```
