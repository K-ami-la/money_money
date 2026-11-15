# Money_money – partage des frais entre amis
Un petit clone de Tricount en un seul fichier HTML, sans serveur, hébergeable gratuitement sur GitHub Pages.

## Fonctionnalités
- Ajouter des participants et des dépenses (qui a payé, pour qui)
- Soldes de chacun et liste minimale des remboursements (« Paul doit 12 € à Marie »)
- Données enregistrées dans le navigateur
- **Partage par lien** : toutes les données sont dans l'URL, il suffit d'envoyer le lien
- Export / import en fichier `.json`

## Mettre le site en ligne sur GitHub Pages
1. Créez un compte sur https://github.com si besoin.
2. Cliquez sur **New repository**, nommez-le par exemple `minicount`, cochez **Public**, puis **Create repository**.
3. Cliquez sur **uploading an existing file**, glissez `index.html` et `README.md`, puis **Commit changes**.
4. Allez dans **Settings → Pages**. Dans *Source*, choisissez **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
5. Après 1 à 2 minutes, le site est disponible à l'adresse :
   `https://VOTRE-PSEUDO.github.io/minicount/`

## Comment partager avec les amis
1. Onglet **Groupe** → ajoutez les prénoms.
2. Ajoutez les dépenses.
3. Onglet **Groupe** → **Copier le lien de partage** et envoyez-le (WhatsApp, SMS…).
4. Si un ami ajoute une dépense, il renvoie son nouveau lien au groupe : c'est lui qui contient la version à jour.

> Limite : il n'y a pas de base de données partagée, donc deux personnes qui modifient en même temps auront deux versions différentes. Pour une vraie synchronisation en temps réel, on peut brancher une base gratuite comme Firebase ou Supabase.
> 
