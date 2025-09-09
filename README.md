# Pizza-sales-analysis
Ce projet simule l’analyse des ventes d’une pizzeria afin d’extraire des insights business concrets à partir de données transactionnelles.
Il combine deux approches :
- **SQL (MySQL)** : création de la base de données, exploration et analyses.  
- **Power BI** : visualisation des résultats sous forme de dashboard interactif.  

---

## Jeux de données
Les données utilisées proviennent de fichiers CSV simulant un vrai environnement e-commerce :
- **orders.csv** : informations sur les commandes (date, heure, ID)  
- **order_details.csv** : détails des commandes (produits, quantités)  
- **pizzas.csv** : tailles et prix des pizzas  
- **pizza_types.csv** : catégories et noms des pizzas  

---

## 🗄 Partie SQL
### Étapes
1. **Création de la base et des tables** 
2. **Analyses basiques** → [`basic_query.sql`]([sql/basic_query.sql](https://github.com/Housna77/Pizza-sales-analysis/blob/main/basic%20query.sql))  
   - CA total, nombre de commandes  
   - Pizza la plus chère, taille la plus vendue  
   - Top 5 pizzas par quantité  
3. **Analyses intermédiaires** → [`intermediate_query.sql`]([sql/intermediate_query.sql](https://github.com/Housna77/Pizza-sales-analysis/blob/main/intermediate%20query.sql))  
   - Répartition des ventes par catégorie  
   - Distribution des commandes par heure  
   - Moyenne de pizzas commandées par jour  
   - Top 3 pizzas par revenus  
4. **Analyses avancées** → [`advance_query.sql`]([sql/advance_query.sql](https://github.com/Housna77/Pizza-sales-analysis/blob/main/advance%20query.sql))  
   - Contribution de chaque catégorie au CA  
   - Revenus cumulés dans le temps  
   - Classement des pizzas par catégorie  

---

## Partie Power BI
Un dashboard interactif a été construit à partir des résultats SQL et des données CSV.  
👉 [Télécharger le dashboard (.pbix)](https://drive.google.com/file/d/1sSQ7K40QMQBuSazgXq1Oppa4zZwrtbXx/view?usp=drive_link)  


### KPIs suivis :
- **Total Sales** (CA total)  
- **Total Orders** (nombre de commandes)  
- **Average Order Value** (panier moyen)  
- **Total Quantity Sold**  
- **Avg Pizza per Order**  

### Principaux graphiques :
- Répartition du CA par **catégorie**  
- **Top 5 pizzas** par revenu  
- Ventes par **taille de pizza**  
- Ventes par **mois **  
  

---

##  Insights principaux
- La taille **Large** est la plus vendue (45% du CA).  
- Les catégories **Classic & Supreme** dominent les ventes.  
- En moyenne, un client commande **2,3 pizzas par commande**.  
 

---

## Compétences mises en avant
- **SQL** : création de DB, jointures, agrégations, fonctions analytiques.  
- **Data Cleaning** : préparation et typage des données dans Power Query.  
- **Data Visualization** : design d’un dashboard clair et interactif dans Power BI.  
- **Business Analysis** : interprétation des données pour générer des insights actionnables.  

---

##  Conclusion
Ce projet montre un cycle complet de **Data Analyst** :  
de la **création d’une base SQL** à la **visualisation Power BI**, en passant par des **analyses business orientées e-commerce**.

<img width="1346" height="732" alt="dashboard" src="https://github.com/user-attachments/assets/31401838-b152-4581-ad52-fededf79b91c" />

