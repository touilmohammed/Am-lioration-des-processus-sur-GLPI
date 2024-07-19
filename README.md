# Amelioration-des-processus-sur-GLPI


 Le fichier : glpi\marketplace\formcreator\ajax\formanswer.php :
 
 Redirection du créateur du ticket vers la page du ticket créé en respectant les critères pour les cibles, pour la facilitation de l’interface pour les utilisateurs des formulaires ;



Le fichier : glpi\plugins\fields\inc\containerdisplaycondition.class.php

De base, la catégorie ITIL n’était pas une option pour les conditions, d’où la 
nécessité d’un autre développement pour ajouter les catégories ITIL dans les 
options de recherche pour les conditions ;



 Le fichier : glpi\src\RuleTicket.php
 
Ajout des entité comme actions pour les règles métier pour les tickets;



Le fichier : glpi\src\CommonITILObject.php

Masquage conditionné de l'option d'ajout d'une solution pour les tickets par les droits des profils;



le fichier : glpi\plugins\transferticketentity\inc\ticket.class.php

Changement du nom de l'onglet créer pour l'utiliser pour les réclamation fondée;



Le fichier : glpi\plugins\transferticketentity\front\ticket.form.php

assignation des status "en attente" aux tickets transferés;
