# 🎬 JustStreamIt

Projet Front-End développé dans le cadre du parcours développeur web OpenClassrooms.  
Cette application affiche les films les mieux notés à partir d’une API locale, avec une interface responsive et interactive.

---

## 🚀 Fonctionnalités

- 🎞️ Mise en avant du **meilleur film**
- ⭐ Affichage des films les mieux notés par l’API
- 🔎 Filtrage par catégories (Mystery, Comedy, etc.)
- 🔁 Ouverture d'une **modale** avec les détails du film
- 📱 **Responsive design** : optimisé pour mobile, tablette et desktop

---

## 🧰 Technologies utilisées

- **HTML5** / **Tailwind CSS**
- **JavaScript (vanilla)**
- API REST locale : `http://localhost:8000/api/v1/titles`

---

## 🛠️ Installation de l'API (backend)

L’application utilise une API REST locale fournie dans le projet `OCMovies-API`.

### Étapes pour l’installer :

1. **Cloner le dépôt backend (OCMovies-API)** :
   ```bash
   git clone https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR.git
   cd OCMovies-API-EN-FR
   ```

2. **Créer un environnement Python (optionnel mais recommandé)** :
   ```bash
   python -m venv env
   source env/bin/activate  # ou `env\Scripts\activate` sous Windows
   ```

3. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```

4. **Lancer le serveur local** :
   ```bash
   uvicorn main:app --reload
   ```

5. L’API sera disponible à l’adresse :
   ```
   http://localhost:8000/api/v1/titles/
   ```

⚠️ Assure-toi de lancer ce serveur avant d'ouvrir `index.html`, sinon les films ne pourront pas s'afficher.

---

## 🗂️ Lancement du projet (Front-End)

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/sRuiiit/JustStreamIt.git
   cd JustStreamIt
   ```

2. Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, etc.).

---

## 📦 Déploiement GitHub Pages

Le projet peut être visualisé en ligne ici :  
➡️ [https://sRuiiit.github.io/JustStreamIt/](https://sRuiiit.github.io/JustStreamIt/)

---

## 🧑‍💻 Auteur

Projet réalisé par **Steve Raffner** dans le cadre du parcours **Développeur d'applications Python** chez OpenClassrooms.
