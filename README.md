# FIFA 19 Player Classification

Development of a neural network from FIFA 19 dataset to estimate the overall quality of a football player.

After preparing and cleaning the dataset, we end up with 16,134 instances with 22 attributes regarding football player skills: Crossing, Finishing, Heading Accuracy, Short Passing, Volleys, Dribbling, Curve, Free Kick Accuracy, Long Passing, Ball Control, Reactions, Shot Power, Stamina, Strength, Long Shots, Aggression, Interceptions, Positioning, Vision, Penalties, Composure, and Marking.

These attributes have been chosen because their values correlate greater than 0.3 or less than -0.3 with the overall score (the variable to predict), which has been quantile-based discretized into four classes or categories: - Poor football players with overall scores in [46, 62],
- Intermediate for values in [63, 66],
- Good players in [67, 71],
- and Excellent players for overall values in [72, 94]
