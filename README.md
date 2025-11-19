Project Overview
• 	Brief description of the COMPAS dataset and its significance in criminal justice.
• 	Your goal: auditing racial bias in risk scores using AI Fairness 360.
• 	Why this matters: ethical AI, transparency, and fairness in high-stakes decision-making.
2. 🔍 Dataset Details
• 	Source: ProPublica’s COMPAS dataset.
• 	Key features: race, age, priors count, charge degree, two-year recidivism.
• 	Protected attribute: race (African-American vs Caucasian).
3. 🛠️ Tools & Libraries
• 	Python
• 	AI Fairness 360 (IBM)
• 	scikit-learn
• 	matplotlib / seaborn
4. 📊 Methodology
• 	Load and preprocess dataset.
• 	Compute fairness metrics: disparate impact, statistical parity, false positive rate difference.
• 	Train baseline classifier (e.g., logistic regression).
• 	Apply bias mitigation (e.g., reweighing).
• 	Visualize disparities before and after mitigation.
