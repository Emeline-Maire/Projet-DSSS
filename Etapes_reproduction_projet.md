Le projet est reproductible via la procédure ci-dessous:

-Il faut tout d'abord faire tourner le Notebook Première étape, qui permet de renommer les variables, et de créer un data frame commun entre les TDS cis et Trans en
regroupant les données obtenues par scrapping. L'output est : base_clean.csv

-On utilise le data frame base_clean.csv et l'on fait des statistiques descriptives de nos données avec le notebook Stats-Desc. On ajoute des variables dans ce notebook,
la nouvelles base de données est labonnebase.csv

-Ensuite, on labélise l'ensemble de nos variables afin de pouvoir faire nos régressions. On utilise le dataframe labonnebase.csv et on sort comme nouveau dataframe
base_clean_2.csv. le notebook a utiliser pour cet étape est Nettoyage de la base

-Enfin, en utilisant base_clean_2, on regarde les matrices de corrélations entre nos variables et on fait tourner notre modèle de double-Lasso. Le Notebook utilisé à cette étape s'appelle "Régressions" 

On trouvera en plus comme Notebook un notebook "création base de données" qui est le notebook utilisé afin de pouvoir scrapper les données du site internet theEroticReview}
