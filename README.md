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

1. Clonez ce dépôt de code :
   ```bash
   git clone https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR.git
   ```
   Ou téléchargez-le en [ZIP](https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR/archive/refs/heads/master.zip)

2. Rendez-vous dans le dossier :
   ```bash
   cd OCMovies-API-EN-FR
   ```

3. Créez un environnement virtuel :

   - **Windows** :
     ```bash
     python -m venv env
     ```
   - **macOS/Linux** :
     ```bash
     python3 -m venv env
     ```

4. Activez l’environnement virtuel :

   - **Windows** :
     ```bash
     env\Scripts\activate
     ```
   - **macOS/Linux** :
     ```bash
     source env/bin/activate
     ```

5. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

6. Créez et alimentez la base de données :
   ```bash
   python manage.py create_db
   ```

7. Lancez le serveur :
   ```bash
   python manage.py runserver
   ```

L’API sera disponible à l’adresse suivante :
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

2. Ouvrir `index.html` dans un navigateur moderne :

   - **Sur Mac** :
     ```bash
     open index.html
     ```

   - **Sur Windows** :
     ```bash
     start index.html
     ```

---

## 🧑‍💻 Auteur

Projet réalisé par **Steve Raffner** dans le cadre du parcours **Développeur d'applications Python** chez OpenClassrooms.
