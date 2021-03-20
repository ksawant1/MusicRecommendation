# Music Recommendation System

A prediction model that will recommend new music based on the user’s current state of mind.
Our recommendation model adapts content-based filtering. The system is modelled using the following steps: 

Step1: Dataset Clustering (Elbow method ->K-means)
Step2: Data Reduction (PCA)
Step3: Mood Prediction Analysis (a.k.a. Labeling)
Step5: Mood Identification

### Library and software environments
- Python 3.7
- pandas
- sklearn
- preprocessing
- KMeans
- silhouette_score
- matplotlib
- train_test_split
- PCA
- seaborn
- Jupyter
- Install and import above libraires for the code to run  

  
### How to run the project
- Upload the given folder in jupyter 
- Open the RecommendationAlgorithm.ipnyb and run the code in jupyter 
- The above code will generate output.csv in the same folder, which contains songs with labels on mood
- Lastly run the UserInterface.ipnyb , this will be the list of recommended top 10 songs based on the mood of the user.
