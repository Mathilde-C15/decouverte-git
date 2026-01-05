# Les mots clés de git et github

- l versionning réalisé par git va être stocké dans un dossier SPECIAL
- REPOSITORY (dossier technique qui contient les différentses ersions de votre code)
- Dépot LOCAL (celui stocké sur le pc)
- Dépot DISTANT (celui qui va être enregistrer sur github)

# COMMIT

- VERSION DE VOTRE PROJET
- VERSION INCREMENTALE (VERSION QUI NE VA STOCKER QUE LES NOUVEAUTEES)
- `git commit`
- chaque commit à un nom que vous allez lui donner ET une clé primaire (base de données) hash
- 1 COMMIT par fonctionnalité

# FAIRE COMMUNIQUER REPO LOCAL avec REPO DISTANT

- commande envoyer du code du local -> distant : `git push`
- commande qui permet de récupérer du code distant -> local `git pull`

- 1 par jour (fin de journée / début de journée)

- HASH => fonction qui permet de transformer un texte en chaine de caractère (hash)
- MD5() fonction de hashage
- google -> MD5 generator

- bonjour => f02368945726d5fc2a14eb576f7276c0
- a       => 0cc175b9c0f1b6a831c399e269772661

# BRANCH 
- créer des mondes parallèles
- vous avezune nouvelle fonctionalité que vous souhaité créer MAIS vous ne voulez pas que ce code impacte le travaille EXISTANT
- git permet de créer un BRANCH => monde parallèle à votre projet (qui n'impacte pas le projet existant)
- par défaut vous versionnez sur la branch principale du projet qui s'appelle la branch `main`