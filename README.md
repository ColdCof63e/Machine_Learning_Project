# Project
## About dataset
The DOTA 2 win prediction dataset contains records of 10,294 matches, each described
by 117 numerical features. The first column encodes the match outcome (1: Radiant win,
0: Dire win); remaining features represent various aspects of match state, such as hero
selection and player statistics. No missing values were detected. Feature types are all
numerical, with many columns acting as binary flags or counters. Data was sourced from
Kaggle and formatted as CSV files for analysis.
The heroes.json dataset consists of 33 heroes in DOTA 2, each described by 126
attributes. These attributes include hero ID, name, primary attribute (e.g., agility, strength,
intelligence), attack type (melee or ranged), and hero roles (such as Carry, Disabler,
Nuker, Support, etc.). All columns appear to be categorical or text-based, with some
numerical attributes mixed in.

## Learnings implemented:
### Supervise Learning
- Random Forest Classifier
### Unsupervise Learning
- K-means
### PCA + Supervise Learning
### PCA + Unsupervised Learning
