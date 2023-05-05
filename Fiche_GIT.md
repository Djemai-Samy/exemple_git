# Fiche GIT

## Initialision un dépot local

```bash
git init
```

## Ajouter des fichier dans la staging area

### Ajouter un fichier

```bash
git add nom_fichier
```

### Ajouter plusieurs fichier fichier

```bash
git add .
```

---

## Les commits

### Faire un commit

```bash
git commit -m "Votre message pour expliquer ce que vous avez changé ou ajouté"
```

### Lister les commits

```bash
git log
```

---

## Les branches

### Lister les branches

```bash
git branch
```

### Créer une branche

```bash
git branch nom_branche
```

### Changer de branche

```bash
git checkout nom_branche
```

### Supprime une branche

```bash
git branch -d nom_branche
```

### fusionner les branches

```bash
git merge nom_branch
```

## Exercice

1. Créer un dossier et le remplir avec des fichiers sur votre pc
2. Initialiser git
3. Faire un commit
4. Créer un dépot distant sur github
5. pusher/Envoyer le code sur github.

## Dépot distant

### Télécharger un dépot distant

```bash
git clone url_depot
```

### Lier un dépot distant

```bash
git add origin url_depot
```

### Suprimmer le lient

```bash
git remote rm origin
```

### Envoyer le code sur le dépot distant

```bash
git push origin nom_branch
```
