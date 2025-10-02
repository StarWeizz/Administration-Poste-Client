# Exercice 2 - Débutant

## Consignes

1. Créer un fichier secret.txt dans ton répertoire
2. Change les permissions de ce répertoire pour qu'il soit accessible en
lecture/écriture que pour le propriétaire
3. Vérifie qu'un autre utilisateur ne peut pas voir son contenu

<hr>

### Étape 1 : Création du fichier secret.txt

> La commande `touch` permet de créer un fichier vide.

```bash
touch secret.txt
```
![secret.txt](secret.txt.png)

<hr>

### Étape 2 : Changement des permissions du fichier

> La commande `chmod` permet de changer les permissions d'un fichier. L'option `700` permet de donner tous les droits au propriétaire et aucun droit aux autres.

```bash
chmod 700 secret.txt
```

![chmod](chmod.png)

<hr>

### Étape 3 : Vérification des permissions avec un autre utilisateur

> La commande `su` permet de changer d'utilisateur. La commande `cat` permet d'afficher le contenu d'un fichier. Si l'utilisateur n'a pas les permissions nécessaires, un message d'erreur s'affiche.

```bash
su autre_utilisateur
cat secret.txt
```
![su cat](su_cat.png)
![permission denied](permission_denied.png)