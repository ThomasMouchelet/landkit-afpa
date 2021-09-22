# Vérifier que git est installé

```
git -v
git --version
```

# Vérifier si un utilisateur est configuré

```
git config user.name
git config user.email
```

## Configurer un utilisateur

```
git config --global user.name "MyUserName"
git config --global user.email "user@email.com"
```

## Cinitialiser projet

```
git init
```

## Virifier le status des fichiers git

```
git status
```

## Commit state change

```
git add .
git commit -m "message du commit"
```

## Branch

```
git branch
git branch nameOfBranch
git checkout feature nameOfBranch
get merge nameOfBranch
git branch -d feature

git checkout -b nameOfBranch
```

```
git log
git log --oneline
```

## Upload sur le repo github

```
git push origin master
```
