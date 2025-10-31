<h1 align="center">🧠 Quiz interactif sur le droit français</h1>
<p align="center">
  <i>Conçu pour un congrès notarial</i>
</p>


## 🎯 Objectif
Quiz interactif sur le droit français (majorité, PACS, héritage...) avec leaderboard et intégration Google Forms couplé à un Google Sheets.

## 🧩 Fonctionnement
Au départ, j’ai créé toutes les questions dans Google Forms afin de pouvoir récupérer facilement les scores via Google Sheets. </br>
L’objectif : éviter une base de données tout en affichant le classement en temps réel.
## 💻 Interface
Comme je voulais un rendu plus joli et en accord avec la direction artistique de l'étude, j’ai ensuite refait toute l’interface du quiz en HTML, CSS et JavaScript.

<p align="center">
  <img src="Quiz.png" alt="Exemple de question du quiz" width="500"/>
</p>

Le quiz comporte 17 questions.

✅ Une bonne réponse ajoute 1 point.
<p align="center">
  <img src="Quiz.png" alt="Exemple de question du quiz" width="200"/>
</p>

❌ En cas de mauvaise réponse, la correction s’affiche immédiatement.
<p align="center">
  <img src="Quiz.png" alt="Exemple de question du quiz" width="200"/>
</p>

## 🏆 Résultats
À la fin, chaque participant peut voir :

- Son score total
- Son classement parmi tous les participants
<p align="center">
  <img src="Quiz.png" alt="Exemple de question du quiz" width="300"/>
</p>

## 📊 Données et leaderboard

De mon côté, j’utilise Google Sheets comme une base de données en temps réel, ce qui me permet de suivre instantanément les résultats de tous les participants.
<p align="center">
  <img src="Quiz.png" alt="Exemple de question du quiz" width="500"/>
</p>

## 🛠️ Technologies utilisées

- HTML / CSS / JavaScript pour le front-end
- Google Forms pour la création et la collecte des réponses
- Google Sheets pour le stockage et le suivi en temps réel


![Début du quiz](Quiz.png)
