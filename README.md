# Sampling

Sampling is a method used to glean insights about a population by analyzing statistics from a representative subset, sparing the need to examine every individual. To tackle an initial dataset imbalance—763 non-fraudulent cases and only 9 fraudulent cases—an oversampling approach was implemented. This involved generating additional instances of the minority class (fraudulent cases) to match the majority class (non-fraudulent cases), resulting in a balanced dataset consolidated into a single data frame.

The following sampling techniques were utilized:

Simple Random Sampling: Random selection of samples from the population.
Systematic Sampling: Regular interval selection after a random start.
Cluster Sampling: Randomly selecting clusters from the population.
Stratified Sampling: Division of the population into subgroups based on certain criteria.
Bootstrap Sampling: Resampling with replacement to create multiple samples from the original dataset.

Following the generation of five distinct samples using these techniques, five models were applied to each sample. The accuracies of each model for a given sample are summarized in the following table:

![image](https://github.com/Kunalg55/Sampling/assets/142966912/c9a4141a-55e8-4158-8107-ed64e187a838)

In above table, each row corresponds to a sampling technique, and each column represent the accuracy achieved by each model applied to the respective sample generated using that respective technique.


