# Compo_data_Analyst_3.20
* Instructions: Cliquez sur le bouton brut dans le coin supérieur droit de cette boîte. Copiez et collez le modèle dans le document README.md sur votre github. Remplissez les titres, informations et liens là où vous y êtes invité! N'hésitez pas à vous écarter un peu en fonction de votre projet, mais essayez de vous en tenir au format aussi étroitement que possible pour assurer la cohérence entre les projets DSWG. *

# Dataset: Prédiction de vente croisée

#### - État du projet: [Terminé]

## Introduction / objectif du projet
Le but de ce projet est de construire un modèle pour prédire si un client serait intéressé par l'assurance automobile ce qui serait  extrêmement utile pour l'entreprise, car elle pourra ensuite planifier en conséquence sa stratégie de communication pour atteindre ces clients et optimiser son modèle commercial et ses revenus. 



### Méthodes utilisées
* Visualisation de données(numpy pandas , seaborn , matplotlib)
* Modélisation prédictive(KNN, logistic Regression, Xgboost)
* Apprentissage automatique

### Les technologies 
* Python
    

## Description du projet
Votre client est une compagnie d'assurance qui a fourni une assurance maladie à ses clients.Il a maintenant besoin de votre aide pour construire un modèle pour prédire si les assurés (clients) de l'année dernière seront également intéressés par l'assurance automobile fournie par la société.
Une police d'assurance est un arrangement par lequel une entreprise s'engage à fournir une garantie d'indemnisation pour une perte, un dommage, une maladie ou un décès spécifiés en échange du paiement d'une prime déterminée. Une prime est une somme d'argent que le client doit payer régulièrement à une compagnie d'assurance pour cette garantie.
Désormais, afin de prédire si le client serait intéressé par l'assurance véhicule, vous disposez d'informations sur les données démographiques (sexe, âge, type de code de région), les véhicules (âge du véhicule, dommages), la politique (Premium, canal d'approvisionnement), etc.

## Description des données
Variable | Définition
------------ | -------------
id | 	Identifiant unique du client
Gender| Sexe du client
Age | Age du client
Driving_License | 0: le client n'a pas de permis, 1: le client a déjà son permis
Region_Code | Code unique pour la région du client
Previously_Insured | 1: le client a déjà une assurance véhicule, 0: le client n'a pas d'assurance véhicule
Vehicle_Age | Âge du véhicule 
Vehicle_Damage | 1: Le client a eu son véhicule endommagé dans le passé. 0: Le client n'a pas fait endommager son véhicule par le
Annual_Premium | Le montant que le client doit payer en prime dans l'année
Policy_Sales_Channel | Code anonyme pour le canal de sensibilisation du client, c.-à-d. Différents agents, par courrier, par téléphone, en personne, etc.
Vintage | 	Nombre de jours, le client a été associé à l'entreprise
Response | 	1: le client est intéressé, 0: le client n'est pas intéressé


## Contact
* Kacou585@gmail.com
