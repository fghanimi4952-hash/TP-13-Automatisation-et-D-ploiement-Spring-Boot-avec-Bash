#  TP – Automatisation du cycle de vie d'une application Spring Boot avec Bash

Ce projet Spring Boot est configuré avec des scripts Bash pour automatiser le cycle de vie de l'application.

##  Structure du projet

<img width="503" height="692" alt="Capture d’écran 2025-11-25 à 14 56 31" src="https://github.com/user-attachments/assets/58e90f11-dee1-4118-b1be-a99b04c03d0a" />


##  Configuration

- **Port**: 8085
- **Base de données**: H2 (en mémoire)
- **Java**: Version 17 ou supérieure

##  Scripts disponibles

###  run.sh
Lance l'application Spring Boot en arrière-plan.

```bash
./scripts/run.sh
```

###  stop.sh
Arrête le processus Spring Boot en cours d'exécution.

```bash
./scripts/stop.sh
```

###  logs.sh
Affiche les 30 dernières lignes des logs de l'application.

```bash
./scripts/logs.sh
```

###  deploy.sh
Compile le projet et déploie la nouvelle version.

```bash
./scripts/deploy.sh
```

## 🛠️ Installation et utilisation

### 1. Donner les permissions d'exécution aux scripts

```bash
chmod +x scripts/*.sh
```

### 2. Lancer l'application

```bash
./scripts/run.sh
```

### 3. Vérifier les logs

```bash
./scripts/logs.sh
```

### 4. Arrêter l'application

```bash
./scripts/stop.sh
```

### 5. Déployer une nouvelle version

```bash
./scripts/deploy.sh
```
<img width="615" height="875" alt="image" src="https://github.com/user-attachments/assets/81ad3979-4c9a-48a8-886b-cedb6f449d42" />

