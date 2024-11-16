Mushroom Classification Using Naive Bayes

This repository contains a machine learning project that classifies mushrooms as either edible or poisonous based on various features using the Naive Bayes classification algorithm. The dataset includes attributes such as cap shape, cap color, gill attachment, and more.

Dataset

The dataset used in this project contains characteristics of mushrooms and their classification (edible or poisonous). Each row in the dataset represents a mushroom, with several categorical features related to its physical attributes.

The dataset contains Rows: 61069 & Columns: 21.

Features:
1. class: The target variable (edible or poisonous) - p (poisonous), e (edible)
2. cap-diameter: Diameter of the mushroom cap
3. cap-shape: Shape of the mushroom cap (e.g., convex, flat)
4. cap-surface: Surface type of the mushroom cap (e.g., smooth, scaly)
5. cap-color: Color of the mushroom cap
6. does-bruise-or-bleed: Whether the mushroom bruises or bleeds when cut
7. gill-attachment: Attachment of the gills to the stem (e.g., free, attached)
8. gill-spacing: Spacing between the gills
9. gill-color: Color of the gills
10. stem-height: Height of the stem
11. stem-root: Type of root the stem has (e.g., bulbous, rhizomorphic)
12. stem-surface: Surface type of the stem (e.g., smooth, fibrous)
13. stem-color: Color of the stem
14. veil-type: Type of veil (e.g., universal, partial)
15. veil-color: Color of the veil
16. has-ring: Whether the mushroom has a ring around the stem
17. ring-type: Type of ring (e.g., evanescent, flaring)
18. spore-print-color: Color of the spore print
19. habitat: Habitat in which the mushroom grows (e.g., forest, grassland)
20. season: Season during which the mushroom was found (e.g., autumn, summer)

Objective

The goal of this project is to predict whether a mushroom is edible or poisonous based on its features using the Naive Bayes classification algorithm.

Model Evaluation

The Naive Bayes model has been evaluated based on several metrics:
1. Accuracy: The proportion of correct predictions.
2. Precision: The proportion of positive predictions that are actually correct.
3. Recall: The proportion of actual positives that were correctly predicted.
4. F1-Score: The harmonic mean of precision and recall.
