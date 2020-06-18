# Human-Attention-for-Text-Classification
A comparison of human attention with computational attention mechanisms 


File format:
Input.label,    Input.text,    Answer.Q1Answer,    Answer.html_output

Input.label: Original Yelp label for the review, converted to 0 (negative) or 1 (positive). One and two-star reviews are mapped to 0, four and five-star reviews are converted to 1. 
Input.text: Original review from the Yelp dataset.
Answer.Q1Answer: Sentiment label collected from the annotator
Answer.html_output: Human attention map (HAM) collected from the annotator. 

You can use the "visualize_single_map>empty-template.html" file for visualizing a single HAM. You should copy "Answer.html_output" field into the relevant part in this file. 

You can use the "generate_ham>generate-human-attention.py" file for converting the html format HAM into a binary vector. 


