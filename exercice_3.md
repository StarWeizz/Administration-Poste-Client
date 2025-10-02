# Exercice 3 - Intermédiaire

## Consignes

1. Affichez la liste des processus et montrez-moi celui qui utilise le plus de ram
2. Utilisez la commande « nice » pour modifier la priorité d'un processus
3. Terminez un processus grave à son PID

<hr>

### Étape 1 : Afficher les processus

> La commande `ps aux` affiche la liste de tous les processus en cours d'exécution. L'option `--sort=-%mem` permet de trier les processus par utilisation de la mémoire, du plus élevé au plus bas. La commande `head -n 1` affiche la première ligne du résultat, qui correspond au processus utilisant le plus de RAM.

```bash
ps aux --sort=-%mem | head -n 1
```

![ps aux](ps_aux.png)

<hr>

### Étape 2 : Modifier la priorité d'un processus

> La commande `renice` permet de modifier la priorité d'un processus. L'option `-n` permet de définir la nouvelle priorité (valeur entre -20 et 19, où -20 est la plus haute priorité). Le PID est l'identifiant du processus que vous souhaitez modifier.

```bash
renice -n 10 -p <PID>
```

![renice](renice.png)

<hr>

### Étape 3 : Terminer un processus

> La commande `kill` permet de terminer un processus en utilisant son PID. L'option `-9` force la terminaison immédiate du processus.

```bash
kill -9 <PID>
```

![kill](kill.png)
