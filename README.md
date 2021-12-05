# fight-club
Ruby Rails playground


Bienvenue dans notre toute nouvelle application, que j'ai nommée.... ! 'Fight club Online'

Nous voulons ici organiser des combats de pouces clandestins.  
Nous organisons régulièrement des evenements en tout genre ou le meilleur pouce l'emporte.  
Nous avons besoin d'une application qui nous permet de monitorer notre activité afin de promouvoir notre sport préféré.  


Nos règles:
- Seulement 2 combattants par combat
- On peut parier une fois que les 2 combatattants connus, pas avant
- Le pari minimum est de 5€ et l'ensemble ne doit pas dépasser 100€ pour des raisons de comptabilité

Dans un premier temps, j'ai besoin: 

D'une application qui permet:
# A mes Utilisateurs de:
- S'inscrire à des combats
- Consulter des combats
- Créer des combats
- Consulter son compte de crédit
- Regarder une vidéo Youtube pour gagner des crédits sur le site: https://www.youtube.com/watch?v=KxGRhd_iWuE
- Parier sur un combat avec ses crédits

----------

# A mes Visiteurs de:
- Consulter les combats
- Consulter les paris

----------


Ici, on est auto administré.  
Du coup certains Utilisateur sont eux même Admin.  
Pour plus de simplicité, on ajoutera un boolean sur le model User qui permettra d'identifier les droits de celui-ci  

# A mes Administrateur de:
- Faire tout ce qu'un utilisateur peut faire
- Blacklist un Utilisateur malveyant
- Supprimer un combat
- Clore les paris d'un combat



