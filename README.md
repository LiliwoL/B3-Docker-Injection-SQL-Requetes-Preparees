# Docker Injection SQL et Requêtes préparées

Container Docker pour suivre le cours Injection SQL et Requêtes préparées

# Lancement

Clonez le dépôt

```bash
git clone https://github.com/LiliwoL/B3-Docker-Injection-SQL-Requetes-Preparees
```

Allez dans le dossier **Docker-Injection-SQL-Requetes-Preparees**

```bash
cd B3-Docker-Injection-SQL-Requetes-Preparees
```

Lancez le container

```bash
sh bin/start
# ou utilisez la commande
docker-compose up -d
```

---

# Accès aux containers

## Web

http://localhost:8000/list.php

## PhpMyAdmin

http://localhost:8081

---

# Déroulé d TP

## Etape 1

Accédez à la page web de l'application à l'adresse suivante:
http://localhost:8000/list.php

Ensuite à :
http://localhost:8000

> Vous devez sécuriser le script index.php en utilisant des requêtes préparées.

## Etape 2

Vous devez sécuriser le script edit.php

http://localhost:8000/edit.php?id=3

## Etape 3

Vous devez sécuriser le script insert.php

## Etpae 4

Vous devez rédiger le script delete.php