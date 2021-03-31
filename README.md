# All-About-Movies

Topic Model Visualization can be found at: <a href="https://topic-model-viz.herokuapp.com/#topic=0&lambda=1&term=">link<a>
  
Flower plots can be found at: <a href="https://github.com/prabhnoor0212/All-About-Movies/tree/main/experiemnts/flower_visualization">link</a>  
  
 

## 1) User and Movies Neural Embeddings generation: <a href="https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/USER_MOVIE_EMBED_MISCELLANEOUS.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - Movie Latent Vectors
  - User Latent Vectors
  - Movie Community Detection and basic Exploratory Data Analysis
  - Input JSON for FLOWER PLOT preparation
SUMMARY OF MAJOR RESULTS:
  - Distribution of average_movie_ratings and avg_votes contrast nicely over various movie communities
  
## 2) Movies Community Analysis: <a href="https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/Movie_Community_Analysis.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - Analysis around the driving factors for movie communities
SUMMARY OF RESULTS:
  - Plot Keywords' wordclouds look quite similar across all the movie communities
  - Genre distribution shows some differences among various communities however, not too much.
  - Release year seems to vary quite strongly for various communites. Communities having movies from around 1980-early 2000s seemed to have much higher ratings than more of the        recent ones.
  - Topics (from topic modelling) distribution seems to also vary quite strongly among communities. Documentries and historical movies seemed to have higher ratings as compared to    teenage dramas
  
## 3) User Community Analysis: <a href= "https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/UserCommunities.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - User Communities detection
  - User Communities EDA
  - User Communities Deep Dive - insights
  
## 4) Neural Topic Modelling: <a href= "https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/NeuralTopicModelling.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - Topic Modelling for Movie Plots
  - Visualization generation for Topics and their terms
  
## 5) Production House Analysis: <a href= "https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/ProductionHouse.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - Production House Creation based on movie ratings distribution
  - Community Detection
  - Analysis
  
## 6) Actor Analysis: <a href="https://github.com/prabhnoor0212/All-About-Movies/blob/main/experiemnts/ActorsAnalysis.ipynb">notebook</a>

NOTEBOOK CONTENTS:
  - Actors Graph Creation based on movie ratings distribution
  - Community Detection
  - On the found communities, Sub-graphs creation based on topic distribution
  - Analysis

## 7) Knowledge Graph Creation Utilities: <a href = "https://github.com/prabhnoor0212/All-About-Movies/blob/main/KnowledgeGraphCreation.ipynb"> notebook </a>

NOTEBOOK CONTENTS:
  - Basic data exploration and processing 
  - Inserstion of entities and relationships in Neo4j DBMS 
  - Inserted entites are :  Movie, Genre, Actor,Director, Production Company, Release year
  - Created relationships are: Has_Genre, Acted_By, Directed_By, Produced_By, Released_In

## 8) Knowledge Graph Embedding Models Comparative Study: <a href = "https://github.com/prabhnoor0212/All-About-Movies/blob/main/KnowledgeEmbeddingModelsComparativeStudyPart1.ipynb"> notebook part1 </a> <a href = "https://github.com/prabhnoor0212/All-About-Movies/blob/main/KnowledgeEmbeddingModelsComparativeStudyPart2.ipynb"> notebook part2 </a>


NOTEBOOK CONTENTS:
  - Installation of required libraries 
  - Training and testing of the compared models (TransE, DistMult, ComplEx, and RotatE)
  - Testing of embeddings for prediciton of head, tail and relationship tuples.
  




