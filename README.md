# Zero shot classification for French professional training titles

1000s of training programs are available in France aimed at all types of jobs and competency levels. This script allows to match professional trainings to their corresponding area and job positions, in order to better map available trainings and identify deficiencies in certain skills or competencies.

The matching relies on a zero-shot approach using pre-trained French Word2Vec embeddings and cosine similarity. A list of professional training titles and descriptions as well as a list of positions and descriptions are embedded, max-pooled and compared via cosine similarity. The most similar professional training and positions are matched. Word2Vec vectors are fine-tuned with a labor market thesaurus to better represent specific labor market terms.

This script was primarily used to match professionnal training titles but can be generalized to any task involving zero-shot classication in French.

Pre-trained French embeddings available: https://fauconnier.github.io/

# Classification en zero-shot d'intitulés de formations professionnelles

Des milliers d'offres de formations professionnelles sont disponibles en France, elles sont destinées à l'ensemble des secteurs, emplois et niveaux de compétences. Ce script permet de matcher ces offres de formation à leurs secteurs et postes afin de mieux cartographier l'offre de formation disponible et identifier les déficits pour certaines compétences.

Ce matching repose sur une approche dite "zero-shot" basée sur des word embeddings Word2Vec Français pré-entrainés et la similarité cosinus. Une liste d'intitulés de formations professionnelles, leurs descriptions ainsi qu'une liste de postes sont vectorisés, max-pooled et comparés via similarité cosinus. Les formations professionelles et les postes les plus similaires sont matchés. Les word vectors Word2Vec sont ré-entrainés sur un thésaurus dédiés au marché de l'emploi pour affiner les représentations des mots spécifiques à ce sujet.

Ce script a été principalement utilisé pour classifier des offres de formations mais peut aussi être généralisé à n'importe quelle tâche de classification zero-shot en Français.

Les word vecteurs pré-entrainés sont disponibles à: https://fauconnier.github.io/
