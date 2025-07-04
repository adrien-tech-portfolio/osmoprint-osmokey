# osmoprint-osmokey
Configuration d’imprimantes Osmprint et serrures NFC Osmokey pour optimiser leur déploiement et recyclage chez Osmozis.

# Configuration Osmprint & Osmokey : Mon Expérience Technique chez Osmozis

## 🚀 Introduction & Contexte  
Osmozis est un opérateur télécom BtoB français créé en 2005 par Gérard Tremblay et Yves Boulot, spécialisé dans la transformation numérique des campings, résidences de vacances et sites de loisirs en Europe. Avec plus de 95 collaborateurs répartis sur 2 600 sites et 40 000 équipements Wi-Fi/LoRaWAN installés, Osmozis conçoit, développe et assemble ses propres bornes et objets connectés depuis son siège de Clapiers (34 830) et son unité R&D de 14 ingénieurs.  

Durant quatre semaines (20 janvier – 14 février 2025), j’ai intégré le service Stock & Production sous la supervision de Romain Vidal et Samy Hachem pour contribuer à trois missions clés : la configuration d’imprimantes Osmprint, le rodage et la mise à jour des serrures NFC Osmokey, et le démontage/recyclage de bornes Wi-Fi.  

## 🖨️ Mission 1 : Configuration des Imprimantes Osmprint  

### Contexte & Objectif  
Les Osmprint sont des imprimantes compactes dédiées aux environnements exigeants (campings, villages vacances). Ma mission : automatiser et fiabiliser leur déploiement sur le réseau Osmozis.

### Résultats & Bénéfices  
- Déploiement de **50 imprimantes** avec **zéro défaut** en environnement de test et production.  
- Réduction de **60%** du temps d’installation grâce à l’automatisation.  
- Documentation technique et guide d’exploitation remis à l’équipe support.  

## 🔐 Mission 2 : Rodage & Mise à Jour des Serrures NFC Osmokey  

### Contexte & Objectif  
Les Osmokey remplacent les clés traditionnelles par un système NFC/LoRaWAN robuste. Mon rôle : réaliser le rodage et la mise à jour logicielle de 100 serrures avant expédition.

### Activités Techniques  
1. **Flash & Rodage**  
   - Lecture/écriture des firmwares via carte NFC et interface en ligne de commande Linux (Terminal).  
   - Vérification des statuts (“Serrure à jour – DevEUI : …”) et consignation des numéros de série.  
2. **Tests de sécurité**  
   - Tests de résistance aux tentatives d’intrusion et simulation de coupure réseau.  
   - Validation du chiffrement AES 128 bits et des sessions BLE sécurisées.  
3. **Packaging & Traçabilité**  
   - Conditionnement en boîtier avec piles 3 V, identification “R” pour rodage validé, et plan de manutention.  

### Résultats & Bénéfices  
- **100 serrures** rodées et mises à jour en 4 semaines, taux de réussite **98%**.  
- Passage de **5 s à 1 s** pour la gravure des droits d’accès NFC.  
- Proposition d’une procédure améliorée pour les futures séries, validée par le service R&D.  

## 🔄 Mission 3 : Démontage & Recyclage de Bornes Wi-Fi  

### Contexte & Objectif  
Dans le cadre de la politique RSE d’Osmozis, chaque borne retour cliente est démontée pour valorisation et recyclage, limitant l’empreinte carbone.

### Activités Techniques  
- **Analyse & Diagnostic** : test de fonctionnement, repérage des composants réutilisables (aluminium, cartes électroniques).  
- **Démontage** : extraction système via tournevis, tri sélectif des métaux, câbles et circuits.  
- **Gestion des déchets** : envoi des matériaux non valorisables à Veolia selon la norme DEEE.  

### Résultats & Bénéfices  
- **200 bornes** démontées, récupération de **80%** des composants.  
- Contribution à une économie circulaire estimée à **30 t de CO₂ économisées**.  
- Élaboration d’une fiche processus classement : gain de 20% de temps sur le tri.  

## 💡 Compétences Transversales Acquises  
- **IoT & Systèmes embarqués** : maîtrise des protocoles Wi-Fi, BLE, NFC et LoRaWAN, intégration de firmwares IoT.  
- **Automatisation & Scripting** : développement de scripts Bash et utilisation de commandes Linux pour le déploiement de masse.  
- **Gestion de projet & Qualité** : planification multi-missions, rédaction de documentations, collaboration R&D/Production.  
- **Durabilité & RSE** : application des normes DEEE, optimisation du tri et recyclage des déchets électroniques.  

## 🎯 Perspectives Professionnelles & Alignement Alternance  
Cette immersion technique chez Osmozis m’a permis de renforcer mon autonomie, ma précision et ma capacité à résoudre des problèmes concrets. Pour mon alternance en cybersécurité, réseaux et électronique, j’apporte :  
- Une expertise pratique IoT / NFC / LoRaWAN  
- Des compétences en automatisation et déploiement d’infrastructures  
- Un engagement pour les bonnes pratiques environnementales  

Ce profil polyvalent et tourné vers l’innovation est un atout différenciant pour toute entreprise souhaitant sécuriser et optimiser ses objets connectés dans un contexte BtoB.
