# Capstone-Project-Machine-Learning
# Introduction

This problem was originally proposed by Prof. I-Cheng Yeh, Department of Information Management Chung-Hua University, Hsin Chu, Taiwan in 2007. It is related to [his research](https://www.researchgate.net/publication/222447231_Modeling_of_Strength_of_High-Performance_Concrete_Using_Artificial_Neural_Networks_Cement_and_Concrete_research_2812_1797-1808) in 1998 about how to predict compression strength in a concrete structure.

" Concrete is the most important material in civil engineering " - Prof. I-Cheng Yeh

Concrete compression strength is determined not just only by water-cement mixture but also by other ingredients, and how we treat the mixture. Using this dataset, we are going to find “the perfect recipe” to predict the concrete’s compression strength, and how to explain the relationship between the ingredients concentration and the age of testing to the compression strength.

Concrete: “Can you show me your recipe?”

How much the increment/decrement of the structure’s compression strength when you add more water? Can the concrete structure have more compression strength when you left it to rest longer?

The goal is to **build a linear regression model that fulfills all assumptions. Interpret how each ingredient and age of testing affect the concrete compression strength**.

# Conclusion

The goal of this capstone project was to develop a model that accurately predicts the compressive strength of concrete based on its ingredients and age, and to identify the optimal composition for maximizing strength. Through a systematic approach involving data preprocessing, exploratory data analysis, model building, and statistical testing, we successfully achieved this goal.

1. Goal Achievement:

- The primary goal of predicting concrete compressive strength was achieved with a high degree of accuracy. The ensemble model, which combined predictions from the Box-Cox transformed linear regression model and a Random Forest model, demonstrated strong predictive performance with a Mean Absolute Error (MAE) of 3.48 and an R-squared value of 0.93 on the validation dataset. These metrics indicate that the model is both precise and reliable in predicting concrete strength.

2. Machine Learning for Problem-Solving:

- This project demonstrates that machine learning can effectively solve the problem of predicting concrete compressive strength. By leveraging regression techniques and advanced machine learning methods such as Random Forests, we were able to model the complex relationships between ingredients, age, and the resulting strength. The use of transformations, interaction terms, and ensemble methods further enhanced the model’s ability to capture non-linear relationships and improve accuracy.

3. Model Used and Performance:

- We employed an ensemble approach combining the strengths of a Box-Cox transformed linear regression model and a Random Forest model to address non-linearity, multicollinearity, and other model assumptions. The final ensemble model exhibited excellent performance metrics:

- MAE: 3.49

- R-squared: 0.93

  with result that implement to test dataset:

- MAE: 7.36

- R-squared: 0.79

- These results demonstrate that the ensemble model is capable of making highly accurate predictions, which is crucial for optimizing concrete mix designs.

4. Potential Business Implementation:

- The insights gained from this project have significant implications for the construction industry. By identifying the optimal mix of concrete ingredients, companies can produce stronger and more durable concrete, leading to improved structural integrity and longer lifespans for buildings and infrastructure. This optimization enhances safety and offers cost savings by reducing the need for excessive materials.

- The model developed in this project can be integrated into concrete mix design software, enabling engineers to input ingredient quantities and receive real-time predictions of compressive strength. This tool can help streamline the mix design process, ensuring that the most effective combinations are used for specific construction needs, thereby improving efficiency and reducing material waste.

In conclusion, this capstone project successfully addressed the challenge of predicting and optimizing concrete compressive strength using an ensemble of machine learning models. The final model's strong performance and the identification of an optimal mix composition provide valuable insights that can be directly applied in real-world construction scenarios, offering both technical and economic benefits.
