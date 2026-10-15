# 🌤️ Weather App

Une application météo simple et élégante qui affiche la météo actuelle de n'importe quelle ville du monde, grâce à l'API OpenWeatherMap.

## ✨ Fonctionnalités

- Recherche de la météo par nom de ville
- Affichage de la température, de l'humidité et de la vitesse du vent
- Icône météo dynamique (nuageux, pluie, brume, neige, bruine)
- Message d'erreur si la ville est introuvable
- Recherche avec le bouton ou avec la touche **Entrée**
- Design moderne et responsive

## 🛠️ Technologies utilisées

- **HTML5**
- **CSS3** (dégradé, flexbox, design responsive)
- **JavaScript** (Fetch API, async/await)
- **[OpenWeatherMap API](https://openweathermap.org/api)**

## 📁 Structure du projet

```
weather-app/
├── index.html
├── style.css
├── script.js
├── README.md
└── image/
    ├── search.png
    ├── rain.png
    ├── clouds.png
    ├── mist.png
    ├── snow.png
    ├── drizzle.png
    ├── humidity.png
    └── wind.png
```

## 🚀 Installation

1. **Clone le dépôt** :
   ```bash
   git clone https://github.com/tahiri-devv/Weather-App.git
   cd Weather-App
   ```

2. **Obtiens une clé API gratuite** sur [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

3. **Configure ta clé** en ajoutant ces deux lignes au début de `script.js` :
   ```javascript
   const apiKey = "TA_CLE_API";
   const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
   ```

4. **Ouvre `index.html`** dans ton navigateur (ou utilise l'extension *Live Server* de VS Code).

## 💡 Utilisation

1. Tape le nom d'une ville dans la barre de recherche (ex. : `Paris`, `Rabat`, `New York`).
2. Clique sur le bouton de recherche ou appuie sur **Entrée**.
3. La météo de la ville s'affiche : température, humidité et vitesse du vent.

Si le nom de la ville est incorrect, un message d'erreur apparaît.

## 🔒 Sécurité

Ne publie jamais ta clé API sur un dépôt public. Pour un vrai déploiement, garde la clé côté serveur ou utilise des variables d'environnement.

## 🔮 Améliorations possibles

- Ajouter la prévision sur plusieurs jours
- Détecter la position de l'utilisateur (géolocalisation)
- Ajouter un mode sombre / clair
- Gérer d'autres conditions météo (ciel dégagé, orage, etc.)
- Ajouter un sélecteur d'unités (°C / °F)

## 📄 Licence

Ce projet est sous licence MIT. Tu peux l'utiliser et le modifier librement.

## 👤 Auteur

Créé par **Mohamed Tahiri** — [GitHub](https://github.com/tahiri-devv)
