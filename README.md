# 🌟 TP – Automatisation du cycle de vie d'une application Spring Boot avec Bash

Ce projet Spring Boot est configuré avec des scripts Bash pour automatiser le cycle de vie de l'application.

## 📋 Structure du projet

```
ens-springbash/
 ├── src/
 │   ├── main/java/ma/ens/springbash/
 │   └── main/resources/
 ├── scripts/
 │   ├── run.sh
 │   ├── stop.sh
 │   ├── logs.sh
 │   └── deploy.sh
 ├── pom.xml
 └── README.md
```

## 🚀 Configuration

- **Port**: 8085
- **Base de données**: H2 (en mémoire)
- **Java**: Version 17 ou supérieure

## 📜 Scripts disponibles

### 🟢 run.sh
Lance l'application Spring Boot en arrière-plan.

```bash
./scripts/run.sh
```

### 🔴 stop.sh
Arrête le processus Spring Boot en cours d'exécution.

```bash
./scripts/stop.sh
```

### 🟡 logs.sh
Affiche les 30 dernières lignes des logs de l'application.

```bash
./scripts/logs.sh
```

### 🔵 deploy.sh
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

## 📝 Notes

- Les logs sont stockés dans le dossier `logs/`
- L'application utilise une base de données H2 en mémoire (les données sont perdues au redémarrage)
- Le port par défaut est 8085

