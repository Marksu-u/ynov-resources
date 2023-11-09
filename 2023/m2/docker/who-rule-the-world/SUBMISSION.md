# Who Rule The World App - Submission

## Sommaires
1. [Project Team](#project-team)
2. [Start](#start)
3. [Building Images](#building-images)
    - [Worker Service](#worker-service)
    - [Vote Service](#vote-service)
    - [Seed Data](#seed-data)
    - [Result Service](#result-service)
4. [Tag & Push](#tag-et-push)
5. [Docker Compose](#docker-compose)

## Project Team

- Zakaria Amraoui
- Amir Jaafar
- Marc Gapasin

## Start

Dans un premier temps, nous avons récupéré le projet Who-Rule-The-World.

![Capture](images/git-pull.png)

## Building Images

SUite à cela, il est nécéssaire de créer les fichiers docker-compose.build.yaml pour les différents services.

### Worker Service

Tout d'abord avec le Worker service.

![Capture](images/docker-worker.png)

---

### Vote Service</a>

Ensuite le Vote service.

![Capture](images/docker-vote.png)

---

### Seed Data Service

Suivi du Seed Data service.

![Capture](images/docker-seed.png)

---

### Result Service

Et enfin du Result Service.

![Capture](images/docker-result.png)

## Tag et Push

Nous avons ensuite taggés toutes nos images sous le nom who-rule-the-world-imagename.

![Capture](images/tag.png)

Puis nous les avons push dans notre registry.

![Capture](images/push.png)

## Docker Compose

Nous avons créé le ficher docker-compose.build.yaml à la racine projet.

![Capture](images/docker-compose-yaml.png)

Nous avons créé le ficher compose.yaml

![Capture](images/docker-compose.png)

Puis nous avons lancer la commande docker-compose à la racine du projet.

![Capture](images/docker-up.png)