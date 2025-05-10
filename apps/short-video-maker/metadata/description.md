# Short Video Maker

Short Video Maker est une application web permettant de générer automatiquement des vidéos courtes (format "short") à partir de texte et d’images libres de droits. Idéal pour les créateurs de contenu, les marketeurs ou les développeurs qui souhaitent automatiser la production de vidéos virales.

## ✨ Fonctionnalités

- 🔁 Génération automatique de vidéos à partir d’un texte.
- 🖼️ Intégration directe avec l’API **Pexels** pour récupérer des images.
- 🧠 Ajout automatique de voix off et fond musical (via configuration).
- ⚙️ Interface web simple pour lancer ou tester la génération.

## 🚀 Utilisation

Une fois installée, l'application sera accessible sur le port `3123`.

### Exemple d'appel à l'API

```bash
curl -X POST http://localhost:3123/create \
     -H "Content-Type: application/json" \
     -d '{
           "text": "Voici un fait surprenant sur les étoiles...",
           "voice": "female",
           "background_music": true
         }'
```

### Configuration requise
Avant de lancer l'application, vous devez fournir une clé API Pexels dans le champ prévu lors de l'installation.
Obtenez gratuitement une clé sur : https://www.pexels.com/api/

### 📦 Source
Code source : GitHub - gyoridavid/short-video-maker

Image Docker : gyoridavid/short-video-maker:latest-tiny

### 🧠 Auteur
David Győri