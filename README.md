# Mission

## Comment allez-vous procéder ?

Cette mission suit un scénario de projet professionnel. Vous pouvez suivre les étapes pour vous aider à réaliser vos livrables.

Avant de démarrer, nous vous conseillons de :  
- Lire toute la mission et ses documents liés  
- Prendre des notes sur ce que vous avez compris  
- Consulter les étapes pour vous guider  
- Préparer une liste de questions pour votre première session de mentorat

Prêt à mener la mission ?  

---

Vous êtes fraîchement établi en tant qu’expert indépendant spécialisé en intelligence artificielle. Vous participez régulièrement à des concours pour vous faire la main sur de nouveaux sujets.

Durant vos recherches, vous avez découvert l’ONG **“Data is for Good”**, qui propose des challenges de Data Science en ligne sur des thématiques ayant trait au bien commun. Des associations et collectivités publiques sponsorisent ces challenges.

---

## Le site "Data is for Good"

Vous avez décidé de participer à un challenge proposé par la ville de Paris ! Voici le cahier des charges du challenge, que vous avez trouvé sur le site :

Dans ce challenge, ouvert à tous, vous allez réaliser une **analyse exploratoire** avec un jeu de données portant sur les arbres de la ville de Paris, dans le cadre du programme **“Végétalisons la ville”**.

Vos résultats contribueront à une optimisation des tournées pour l’entretien des arbres de la ville. Moins de tournées signifie moins de trajets, et plus d’arbres entretenus.  
Vous aurez ainsi un impact réel sur le futur de la ville de Paris !

---

## Données

Téléchargez le jeu de données des arbres de la ville de Paris. Vous pouvez aussi le consulter dans son contexte sur [opendata.paris.fr](https://opendata.paris.fr).

---

## Règles du challenge

1. Installez votre environnement de développement sur votre ordinateur et créez un environnement virtuel dédié à ce challenge.  
2. Les données doivent être explorées à l’aide de **Python** et de ses librairies.  
3. Vous soumettrez votre analyse sous forme de présentation, contenant les informations suivantes :  
   - Présentation générale du jeu de données  
   - Démarche méthodologique d’analyse de données  
   - Synthèse de l’analyse de données  

Le second livrable prendra la forme d’un **Notebook Jupyter**, documenté pour expliciter les différents traitements, calculs ou graphiques que vous effectuez. Vos explications doivent permettre à un public non technique de comprendre les différentes étapes de votre analyse et votre synthèse.

---

Merci pour votre inscription, et bon courage pour ce challenge ! Que le meilleur gagne !

Dans ce projet, vous devez réaliser une analyse exploratoire en utilisant Python. Attention, cette tâche peut prendre beaucoup de temps ! Soyez vigilant sur le temps passé sur ce projet, en gardant un œil sur la durée estimée du projet, et les compétences évaluées.

---

# Étapes

## Pré-requis

- Avoir installé Python sur l'ordinateur  
- Avoir un environnement virtuel dédié au projet  
- Avoir installé les librairies Python nécessaires, telles que **pandas, numpy et matplotlib**

### Résultats attendus

- Un environnement Python fonctionnel avec toutes les librairies nécessaires installées  
- Un environnement virtuel isolé pour le projet

### Recommandations

- Utiliser un gestionnaire de packages, comme `pip`, pour installer les librairies Python  
- Suivre les instructions de documentation officielle pour installer Python et les librairies

### Points de vigilance

- Vérifier que les versions des librairies installées sont compatibles avec les besoins du projet (ex : Pandas, Numpy, Matplotlib, Seaborn, MissingNo...)  
- Activer un environnement virtuel avant de commencer à travailler sur le projet

**Ressource** : [Documentation de Python](https://docs.python.org/3/)

---

## Pré-requis : Importation des données

- Avoir importé les données du jeu de données dans un DataFrame pandas  
- Avoir compris les informations générales sur les colonnes, les types de données, etc.

### Résultats attendus

- Une vision générale du jeu de données (nombre de colonnes, lignes, types de données)  
- Une compréhension préliminaire des caractéristiques du jeu de données

### Recommandations

- Utiliser `read_csv()` de pandas pour importer les données  
- Utiliser les méthodes `head()`, `info()` et `describe()` pour un aperçu initial

### Points de vigilance

- Vérifier que les données sont correctement importées et cohérentes  
- Identifier les éventuelles valeurs manquantes ou incohérentes

**Ressource** : [Documentation de Pandas](https://pandas.pydata.org/)

---

## Analyse univariée

### Pré-requis

- Avoir chargé correctement le jeu de données  
- Avoir identifié les variables pertinentes à analyser

### Résultats attendus

- Les caractéristiques principales de chaque variable (médiane, moyenne, écart-type...)  
- Des graphiques descriptifs (bar chart ou pie chart pour variables qualitatives, density plot ou boxplot pour variables quantitatives)

### Recommandations

- Utiliser des méthodes statistiques pour calculer les indicateurs (moyennes, médianes, quantiles)  
- Utiliser des graphiques appropriés pour chaque type de variable

### Points de vigilance

- Bien comprendre chaque variable pour interpréter correctement les résultats

**Ressources** :  
- [Documentation de Matplotlib](https://matplotlib.org/stable/users/index.html)  
- [Cours OpenClassrooms : “Nettoyez et analysez votre jeu de données”](https://openclassrooms.com/)

---

## Détection et traitement des valeurs aberrantes

### Pré-requis

- Avoir identifié les valeurs aberrantes dans le jeu de données  
- Avoir défini une approche ou des seuils pour les détecter

### Résultats attendus

- Jeu de données nettoyé, sans valeurs aberrantes identifiées  
- Amélioration de la distribution des données après traitement

### Recommandations

- Remplacer les valeurs aberrantes par des valeurs appropriées, comme `NaN`  
- Utiliser des méthodes statistiques (ex : méthode des interquartiles) pour détecter les valeurs atypiques

### Points de vigilance

- Comprendre les raisons potentielles des valeurs aberrantes  
- Vérifier que le nettoyage améliore la distribution sans créer de distorsions

---

## Synthèse et livrables

### Pré-requis

- Identifier les problématiques métiers des équipes d’entretien de la ville de Paris  
- Identifier comment votre analyse de données peut répondre à ces problématiques

### Résultats attendus

- Notebook Jupyter documenté avec toutes les étapes de l'analyse  
- Synthèse claire des conclusions et insights dans un support de présentation

### Recommandations

- Documenter chaque étape dans le Notebook en expliquant traitements, calculs et graphiques  
- Utiliser le Markdown pour structurer le Notebook et mettre en évidence les points clés  
- Tirer des conclusions et insights pertinents à partir des données

### Points de vigilance

- Assurez-vous que vos explications soient claires pour un public non technique  
- Résumer les principales conclusions de manière concise et percutante
