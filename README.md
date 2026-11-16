# tp-nestjs-ing3

Projet NestJS réalisé dans le cadre du DS de Développement Web (ING3) — SESAME.

Thématique : **Agence de voyages** (ressource `travel`).

## Installation

```bash
npm install
```

## Lancement

```bash
npm run start
```

L'application tourne sur le port défini dans le fichier `.env` (`PORT=8000`).

## Endpoints

| Méthode | Route | Description |
|---|---|---|
| GET | `/` | Retourne « Hello World! » |
| POST | `/travel` | Retourne « Planifier un nouveau voyage ici » |
| GET | `/travel` | Retourne la liste des voyages |
| GET | `/travel/:id` | Retourne un voyage à partir de son id |
