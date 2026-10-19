# Planning Hôpital

Outil web gratuit pour les soignant·e·s qui travaillent en gardes de 12 h dans un hôpital public (fonction publique hospitalière). Il permet de suivre son planning, ses heures, ses congés et ses échanges de gardes depuis son téléphone.

**➡️ Ouvrir l'outil :** `https://VOTRE-PSEUDO.github.io/planning-hopital/`

---

## Ce que fait l'outil

- **Planning** : vous importez les fichiers Excel du service, et votre ligne est retrouvée à partir de votre nom. Vos gardes s'ajoutent à l'agenda de votre iPhone ou à Google Agenda, avec le lieu de chaque garde.
- **Échanges et heures sup** : l'outil propose les collègues avec qui échanger une garde en respectant les règles de repos, pour vous comme pour la personne. Vous pouvez aussi enregistrer une reprise sans retour, un échange décalé ou une garde en heures sup, après vérification des repos et des plafonds.
- **Congés** : vous touchez les jours que vous voulez libres dans un mois pas encore publié. L'outil estime le coût d'après vos plannings précédents, choisit le compteur à utiliser (CA, RTT, fériés, heures sup, CET) et rédige la demande pour le cadre.
- **Compteurs** : obligation annuelle, solde d'heures, CA, RTT, fériés à récupérer et CET versé ou payé, année par année.
- **Bilan** : audit des règles (repos de 12 h, 36 h par semaine, 48 h sur 7 jours, quinzaines, heures sup) et statistiques sur 12 mois.

## Vos données restent chez vous

- Tout est enregistré **dans le navigateur de votre téléphone**. Rien n'est envoyé sur un serveur et il n'y a ni compte ni inscription.
- Sur iPhone, Safari peut effacer ces données au bout d'un certain temps sans visite. Touchez donc **💾 Sauvegarder** régulièrement. Le fichier `.json` obtenu se recharge avec **📂 Recharger**, sur le même appareil ou sur un autre.
- Ce dépôt ne contient que le fichier du site : aucun planning, aucun nom.

## Pour commencer

1. Enregistrez le planning Excel reçu par email dans les fichiers de votre téléphone :
   - **iPhone (Mail)** : touchez la pièce jointe › partager › **Enregistrer dans Fichiers**.
   - **Android (Gmail)** : touchez l'icône **Télécharger** de la pièce jointe.
2. Ouvrez l'outil, puis **Réglages › Mon contrat** : renseignez votre nom, votre base horaire et votre quotité.
3. Onglet **Planning** : touchez **Importer des fichiers Excel** et choisissez le ou les fichiers.
4. Vérifiez le nombre de gardes trouvées par mois, puis utilisez **Échanges** ou **Congés**.
5. Pensez à **💾 Sauvegarder**.

Astuce : sur iPhone, dans Safari, faites **Partager › Sur l'écran d'accueil** pour ouvrir l'outil comme une application.

## Règles utilisées

Les calculs suivent les textes de la fonction publique hospitalière, avec leur source affichée dans l'outil (**Réglages › Règles appliquées**) :

- décret 2002-9 (temps de travail, repos, heures sup) ;
- décret 2002-8 (congés annuels, hors saison, fractionnement) ;
- décret 2002-788 (CET) ;
- circulaire DHOS 2002-240 ;
- instruction DGOS/RH3/2015/3 (gardes de 12 h).

Certaines pratiques dépendent du protocole de chaque hôpital, comme le décompte d'un congé posé sur une garde (en jours ou en heures). Elles se règlent dans **Réglages**.

> Les chiffres sont des **estimations**, à confirmer auprès du cadre ou de la DRH. En cas d'écart, c'est le compteur officiel de l'hôpital qui fait foi.

## Compatibilité

Conçu d'abord pour le téléphone : Safari sur iPhone, Chrome sur Android. Il fonctionne aussi sur ordinateur. Le site tient en un seul fichier `index.html`, publié avec GitHub Pages.

## Mettre à jour le site (mainteneur·euse)

Dans ce dépôt : **Add file › Upload files**, glissez le nouveau `index.html`, puis **Commit changes**. La version s'affiche à côté du titre de l'outil (par exemple **v11**).
