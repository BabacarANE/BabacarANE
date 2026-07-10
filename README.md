<!-- Bannière animée -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey,%20moi%20c'est%20Babacar%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Étudiant%20Développeur%20Full-Stack%20%26%20Data&descAlignY=55&descSize=20" width="100%"/>
</div>

<!-- Badges réseaux -->
<div align="center">
  <a href="https://www.linkedin.com/in/babacar-ane">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://portfoliobabacarane.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139"/>
  </a>
</div>

<br/>

<!-- Présentation -->
## 🚀 À propos de moi

```javascript
const moi = {
  nom:          "Babacar ANE",
  statut:       "Étudiant en ingénierie informatique (EPSI) 🎓",
  localisation: "France 🇫🇷",
  recherche:    "Alternance — Développeur Fullstack / Data Analyst",
  passions:     ["Coder", "Apprendre", "Créer"],
  fun_fact:     "Je debug mieux avec un café ☕"
};
```

<br/>

<!-- Stack technique -->
## 🛠️ Ma Stack

**Langages**

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)

**Backend**

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

**Data & MLOps**

![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/airflow-%23017CEE.svg?style=for-the-badge&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-%230194E2.svg?style=for-the-badge&logo=mlflow&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%23D24939.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232088FF.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

<br/>

<!-- Projets phares -->
## 🌟 Projets phares

### 🔗 [Collab Editor](https://github.com/BabacarANE/collab-editor)
Éditeur de texte collaboratif temps réel — architecture production-grade construite from scratch.

`React` `Tiptap` `Yjs` `Fastify` `PostgreSQL` `Redis` `Kafka` `Kubernetes`

- Édition collaborative temps réel avec convergence garantie (CRDT via Yjs)
- Curseurs et avatars des collaborateurs en direct
- Commentaires ancrés, historique de versions avec diff visuel
- Export PDF / HTML / Markdown, import .md / .docx / .txt
- Recherche full-text, mentions avec notifications, permissions par document
- Mode hors-ligne avec resynchronisation automatique, PWA installable

---

### 📊 [SmartMarket Intelligence](https://github.com/BabacarANE/SmartMarket)
Plateforme data end-to-end d'analyse et de prédiction du marché de l'emploi tech en France.

`Airflow` `dbt` `PostgreSQL` `LightGBM` `MLflow` `Evidently AI` `FastAPI` `Streamlit`

Pipeline complet : collecte automatique des offres d'emploi (APIs France Travail & Adzuna) → nettoyage & transformation dbt → entraînement d'un modèle LightGBM pour la prédiction de salaires → exposition via API REST et dashboard interactif.
