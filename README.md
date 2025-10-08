# Administration Poste Client - Exercices Pratiques

## 📖 Description

Ce dépôt contient une série d'exercices pratiques pour l'apprentissage de l'administration de postes clients sous systèmes Linux/Unix. Les exercices couvrent les commandes de base, la gestion des permissions, l'administration des processus, l'automatisation et la surveillance des logs.

## 📁 Structure du Projet

```
Administration Poste Client/
├── README.md              # Ce fichier
├── exercice_1.md          # Exercice débutant - Gestion des fichiers et logs
├── exercice_1/            # Dossier contenant les captures d'écran de l'exercice 1
├── exercice_2.md          # Exercice débutant - Permissions et sécurité
├── exercice_2/            # Dossier contenant les captures d'écran de l'exercice 2
├── exercice_3.md          # Exercice intermédiaire - Gestion des processus
├── exercice_3/            # Dossier contenant les captures d'écran de l'exercice 3
├── exercice_4.md          # Exercice intermédiaire - Scripts et automatisation
├── exercice_5.md          # Exercice intermédiaire - Analyse des logs SSH
└── exercice_5/            # Dossier contenant les captures d'écran de l'exercice 5
```

## 🎯 Objectifs Pédagogiques

### Exercice 1 - Gestion des Fichiers et Logs (Débutant)
- Manipulation des fichiers avec `ls`
- Redirection de sortie (`>` et `>>`)
- Analyse de logs avec `tail` et `grep`
- Recherche de patterns dans les fichiers

**Compétences acquises :**
- Création et modification de fichiers
- Extraction d'informations depuis les logs système
- Utilisation des opérateurs de redirection

### Exercice 2 - Permissions et Sécurité (Débutant)
- Création de fichiers avec `touch`
- Gestion des permissions avec `chmod`
- Changement d'utilisateur avec `su`
- Vérification des droits d'accès

**Compétences acquises :**
- Compréhension du système de permissions Unix
- Sécurisation des fichiers sensibles
- Test des contrôles d'accès

### Exercice 3 - Gestion des Processus (Intermédiaire)
- Monitoring des processus avec `ps`
- Tri et analyse de l'utilisation des ressources
- Modification des priorités avec `renice`
- Terminaison de processus avec `kill`

**Compétences acquises :**
- Surveillance des performances système
- Gestion des priorités de processus
- Administration des processus en cours

### Exercice 4 - Scripts et Automatisation (Intermédiaire)
- Création de scripts bash pour la sauvegarde
- Gestion des répertoires avec `mkdir -p`
- Planification de tâches avec `cron`
- Rendre les scripts exécutables avec `chmod +x`

**Compétences acquises :**
- Automatisation des tâches administratives
- Programmation bash de base
- Planification de tâches récurrentes
- Gestion des sauvegardes automatiques

### Exercice 5 - Analyse des Logs SSH (Intermédiaire)
- Consultation des logs système avec `journalctl`
- Filtrage temporel des logs (dernières 24h)
- Recherche de patterns de sécurité avec `grep`
- Redirection et sauvegarde des résultats

**Compétences acquises :**
- Surveillance de la sécurité système
- Analyse des tentatives de connexion
- Extraction d'informations critiques des logs
- Documentation des incidents de sécurité

## 🛠️ Prérequis

- Système Linux/Unix ou émulation (WSL, Machine virtuelle)
- Accès au terminal/shell
- Privilèges utilisateur basiques
- Accès root/sudo pour certains exercices

## 🚀 Comment Utiliser ce Dépôt

1. **Exercice 1** - Familiarisez-vous avec les commandes de base et la gestion des logs
2. **Exercice 2** - Apprenez la gestion des permissions et de la sécurité
3. **Exercice 3** - Maîtrisez l'administration des processus
4. **Exercice 4** - Découvrez l'automatisation avec les scripts bash et cron
5. **Exercice 5** - Pratiquez l'analyse des logs de sécurité

Chaque exercice contient :
- Des consignes claires
- Des explications détaillées des commandes
- Des captures d'écran illustratives
- Des exemples pratiques

## 📝 Notes Importantes

- Testez toujours vos commandes dans un environnement sécurisé
- Sauvegardez vos données importantes avant les exercices
- N'hésitez pas à consulter les pages de manuel (`man commande`)
- Les captures d'écran fournies servent de référence visuelle

## 🔧 Commandes Principales Couvertes

| Commande | Usage | Exercice |
|----------|--------|----------|
| `ls` | Liste des fichiers et répertoires | 1 |
| `tail` | Affichage des dernières lignes | 1 |
| `grep` | Recherche de patterns | 1, 5 |
| `touch` | Création de fichiers vides | 2 |
| `chmod` | Modification des permissions | 2, 4 |
| `su` | Changement d'utilisateur | 2 |
| `ps` | Liste des processus | 3 |
| `renice` | Modification de priorité | 3 |
| `kill` | Terminaison de processus | 3 |
| `mkdir` | Création de répertoires | 4 |
| `cp` | Copie de fichiers et répertoires | 4 |
| `crontab` | Planification de tâches | 4 |
| `journalctl` | Consultation des logs système | 5 |

## 📚 Ressources Complémentaires

- [Manuel Linux](https://linux.die.net/man/)
- [Guide des permissions Unix](https://www.gnu.org/software/coreutils/manual/html_node/File-permissions.html)
- [Documentation sur la gestion des processus](https://tldp.org/LDP/tlk/kernel/processes.html)

## 🤝 Contribution

Ces exercices sont conçus dans un cadre pédagogique. Pour toute suggestion d'amélioration ou correction, n'hésitez pas à proposer vos modifications.

## 📄 Licence

Ce contenu est destiné à un usage éducatif dans le cadre des cours d'Administration Poste Client à Ynov.

---

**Année académique :** 2025  
**Institution :** Ynov  
**Cours :** Administration Poste Client