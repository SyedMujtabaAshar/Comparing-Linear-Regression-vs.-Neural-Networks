Recently, I decided to explore how a traditional Linear Regression model compares to a simple Artificial Neural Network (ANN) when it comes to predicting continuous data. I trained both models on the same dataset to see which one performed better on unseen test data.

The results were quite interesting!

The Linear Regression model did a decent job, giving a Mean Squared Error (MSE) of 55.71 and an R² Score of 0.785. This means it explained about 78.5% of the variation in the target values — not bad at all for a basic model.

But when I tested the ANN, which had just two hidden layers, it performed significantly better. It brought down the MSE to 20.33 and boosted the R² Score to 0.921 — meaning it explained over 92% of the variation!

Here’s a quick comparison:

🔢 Metric	📉 Linear Regression	🤖 ANN (Keras)
MSE	55.71	20.33
R² Score	0.785	0.921

📂 Code & Notebook
If you're curious about the implementation, you can check out the full code here:
🔗 GitHub Repository
(Look for the project titled "Regression_ANN_Comparison")

This small experiment showed me how neural networks, even in their simplest form, can uncover deeper patterns that linear models might miss — especially when data relationships aren't purely linear. That said, linear models still have their place when interpretability and speed matter.

Always fun to test theories with real data! 😊# Comparing-Linear-Regression-vs.-Neural-Networks
