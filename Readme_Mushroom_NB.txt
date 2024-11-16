Mushroom Classification Using Naive Bayes
This repository contains a machine learning project that classifies mushrooms as either edible or poisonous based on various features using the Naive Bayes classification algorithm. The dataset includes attributes such as cap shape, cap color, gill attachment, and more.

Dataset
The dataset used in this project contains characteristics of mushrooms and their classification (edible or poisonous). Each row in the dataset represents a mushroom, with several categorical features related to its physical attributes.
The dataset contains Rows: 61069 & Columns: 21.

Features:
class: The target variable (edible or poisonous) - p (poisonous), e (edible)
cap-diameter: Diameter of the mushroom cap
cap-shape: Shape of the mushroom cap (e.g., convex, flat)
cap-surface: Surface type of the mushroom cap (e.g., smooth, scaly)
cap-color: Color of the mushroom cap
does-bruise-or-bleed: Whether the mushroom bruises or bleeds when cut
gill-attachment: Attachment of the gills to the stem (e.g., free, attached)
gill-spacing: Spacing between the gills
gill-color: Color of the gills
stem-height: Height of the stem
stem-root: Type of root the stem has (e.g., bulbous, rhizomorphic)
stem-surface: Surface type of the stem (e.g., smooth, fibrous)
stem-color: Color of the stem
veil-type: Type of veil (e.g., universal, partial)
veil-color: Color of the veil
has-ring: Whether the mushroom has a ring around the stem
ring-type: Type of ring (e.g., evanescent, flaring)
spore-print-color: Color of the spore print
habitat: Habitat in which the mushroom grows (e.g., forest, grassland)
season: Season during which the mushroom was found (e.g., autumn, summer)

Objective
The goal of this project is to predict whether a mushroom is edible or poisonous based on its features using the Naive Bayes classification algorithm.

Model Evaluation
The Naive Bayes model has been evaluated based on several metrics:

Accuracy: The proportion of correct predictions.
Precision: The proportion of positive predictions that are actually correct.
Recall: The proportion of actual positives that were correctly predicted.
F1-Score: The harmonic mean of precision and recall.