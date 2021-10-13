# DataMiningProject
## Group Members
- [Niko Dalla Noce](https://github.com/nikodallanoce)
- [Alessandro Ristori](https://github.com/RistoAle97)
- [Giuseppe Lombardi](https://github.com/)

## Project Description
### Task 1 Data Understanding and Preparation (30 points):
__Task 1.1: Data Understanding:__ Explore the dataset with the analytical tools studied
and write a concise “data understanding” report assessing data quality, the
distribution of the variables and the pairwise correlations.

__Task 1.2: Data Preparation:__ Improve the quality of your data and prepare it by
extracting new features interesting for describing the player profile and his behavior
derivable from matches. These indicators have to be extracted for each player.
Examples of Indicators to be computed are:
- how many times did the player win during a given period
- how many matches the player played in a given period
- a ratio between the previous indicators
- percentage of aces related to the number of first serves made
- number of breakpoints numbers w.r.t. all games
- ….

Note that these examples are not mandatory. You can derive indicators that you
prefer and that you consider interesting for describing the players.

It is MANDATORY that each team defines indicators and their description and when
it is necessary also their mathematical formulation. The profile will be useful for the clustering analysis (i.e., the second project’s task).
Once the set of indicators is computed, the team has to explore the new features for
a statistical analysis (distributions, outliers, visualizations, correlations).

__Subtasks of DU__
- Data semantics for each feature that is not described above and the new one
defined by the team
- Distribution of the variables and statistics
- Assessing data quality (missing values, outliers, duplicated records, errors)
- Variables transformations
- Pairwise correlations and eventual elimination of redundant variables

### Task 2: Clustering analysis (30 POINTS - 32 with optional subtask)
Based on the player’s profiles explore the dataset using various clustering techniques.
Carefully describe your decisions for each algorithm and which are the advantages provided
by the different approaches.
__Subtasks__
- Clustering Analysis by K-means:
  - Identification of the best value of k
  - Characterization of the obtained clusters by using both analysis of the
k centroids and comparison of the distribution of variables within the
clusters and that in the whole dataset
  - Evaluation of the clustering results
- Analysis by density-based clustering:
  - Study of the clustering parameters
  - Characterization and interpretation of the obtained clusters
- Analysis by hierarchical clustering
  - Compare different clustering results got by using different merging
strategies
  - Show and discuss different dendrograms using the different merging
strategies
- Final evaluation of the best clustering approach and comparison of the clustering
obtained
- Optional (2 points): Explore the opportunity to use alternative clustering techniques in the library: https://github.com/annoviko/pyclustering/

