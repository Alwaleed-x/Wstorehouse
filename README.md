# (W)storehouse

Model Results and Analysis:

Three different models were used to analyze the data collected from AI-generated texts compared to human-written texts. The results were presented using Mean Squared Error (MSE), R² Score, and analysis of the differences between the texts using histograms showing the word and character differences.

1. Performance Analysis Using MSE and R² Score:
	•	Mean Squared Error (MSE): The MSE value is 0.0346, indicating that the errors between the model’s predictions and the actual values of the texts are very small. This low value suggests that the model performs with high accuracy.
	•	R² Score: The model achieved an R² score of 0.8519, meaning it explains about 85.19% of the variance in the data. This is a very good score, indicating that the model fits the data very well.

2. Analysis of Word Count Differences:
	•	The histogram (Difference in Character Count) showed that the majority of the differences in word count between the human and AI-generated texts are concentrated around 0, indicating that the AI-generated texts are very similar in length to the human-written ones.
	•	Some outlier cases with large differences in word count were observed, but these cases are rare compared to the texts that show little or no difference.

3. Analysis of Character Count Differences:
	•	The histogram of character differences also showed that the majority of the human and AI-generated texts had differences close to 0, reflecting a strong similarity in length and character count.
	•	While some cases showed significant differences in character counts, these were very few in comparison to the texts with minimal differences.

Conclusions:
	1.	The model performs well, with the R² value indicating that the model successfully explains around 85% of the data, which is a strong indication of the model’s accuracy in its predictions.
	2.	The low MSE suggests that the AI-generated texts are very close to the human-written texts, reflecting the model’s ability to minimize errors in its predictions.
	3.	The histograms show that most of the AI-generated texts are similar in length and character count to human-written texts, indicating the model’s ability to effectively mimic human writing styles.

Recommendations:
	•	Further improvements could be made if additional training data or hyperparameter tuning is used.
	•	The model shows good performance in its current applications, but some minor improvements could help reduce the outlier differences between human and AI-generated texts.
