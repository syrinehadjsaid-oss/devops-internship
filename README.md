# Mon Stage Cloud & DevOps - Projet Portfolio

## Objectif du Projet
Construire, conteneuriser avec Docker, automatiser et déployer en ligne mon propre site web de portfolio professionnel.

## Outils prévus
- Terminal Linux
- Git & GitHub
- Docker
- GitHub Actions
- Hébergement Cloud

## Suivi de mon Avancement
- [x] Semaine 1 : Configuration de l'espace de travail et compréhension de l'architecture.
- [x] Semaine 2 : Linux et gestion des fichiers.
- [x] Semaine 3 : Git et GitHub.
- [x] Semaine 4 : Développement du site et Docker.
- [x] Semaine 5 : CI/CD et déploiement Cloud ( Pipeline validé !).
- [x] Semaine 6 : Documentation finale et présentation.

## Architecture & CI/CD

### Pipeline d'Intégration Continue (GitHub Actions)
Le projet intègre un pipeline de validation automatisé via GitHub Actions (`ci.yml`) qui s'exécute à chaque push sur la branche `main`. Il effectue les actions suivantes :
1. **Vérification des fichiers requis** (`index.html`, `Dockerfile`, `README.md`).
2. **Build de l'image Docker** pour s'assurer que l'application est prête pour le déploiement.
