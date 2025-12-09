# Mini-Projet : Analyse exploratoire des données hospitalières (EDA + Dashboard Streamlit)

Ce projet realise une analyse exploratoire de données (EDA) sur des admissions hospitalières.
Il inclut :
- un **notebook** d’analyse,
- une **application Streamlit** hébergée en ligne,
- un **rapport PDF synthétique**,
- une **documentation complète**.

---

## Objectifs du projet

- Nettoyer et structurer les données hospitalières
- Extraire des statistiques pertinentes
- Visualiser les tendances (âge, pathologies, types d'admission, coûts)
- Mettre en place une application interactive Streamlit

---

## Dataset

Le dataset contient des informations sur :
- Patients (âge, condition médicale, groupe sanguin)
- Hôpitaux (nom, médecin)
- Type d’admission (urgente, élective, etc.)
- Finances (montant facturé)
- Résultats médicaux (tests)

---

## Nettoyage appliqué

- Parsing des dates
- Normalisation des chaînes (titres)
- Typage numérique
- Correction des valeurs aberrantes
- Calcul de la durée de séjour (`LengthOfStay`)
- Suppression des doublons

---

## Visualisations principales (EDA)

Effectuées :
- Histogramme de l’âge
- Répartition des types d’admission
- Relation durée de séjour — coût facturé
- Analyse des pathologies les plus fréquentes

---

## Application Streamlit (Online)

L'application interactive est accessible ici :

**https://hashimi-barry-mini-projec-q09v63iy73-streamlit-app-f1bvvy.streamlit.app**

Fonctionnalités :
- Aperçu du dataset nettoyé
- Graphiques interactifs (Plotly)
- Filtrage par hôpital (si activé)
- Analyse financière dynamique

---

## Exécution locale

### 1) Installer les dépendances
- pip install -r requirements.txt

### 2) Lancer l’application Streamlit
- streamlit run streamlit_app.py


L’application sera accessible à :
http://localhost:8501


---

## Notebook Jupyter

Le notebook `EDA_hospital.ipynb` contient :
- Nettoyage étape par étape
- Statistiques descriptives
- Visualisations
- Observations clés

---

## Rapport PDF

Le rapport `Rapport_EDA_Hospital.pdf` présente :
- Le résumé du dataset
- Méthode de nettoyage
- Résultats EDA
- Captures de visualisations
- Conclusions concises

---

## Technologies

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Plotly
- Streamlit
- Jupyter
- GitHub

---

## Auteur

Mini-projet réalisé par :
- **Ibrahima Gassama (GASI06070000)**
- **Université du Québec à Chicoutimi (UQAC)**
- **Cours : Introduction au Langage Python et à l'environnement**

---


