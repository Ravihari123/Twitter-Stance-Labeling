# Twitter-Stance-Labeling

This study aims to establish a performance baseline for GPT-4 as a social media text annotator. To achieve this, we employ our own dataset of tweets, expertly labeled for stance detection with full inter-rater agreement among three annotators. We experiment with three GPT-4 based learning techniques: Zero-shot, Few-shot, and Zero-shot with Chain-of-Thoughts to create prompts for the labeling task. In this project, we fine-tuned several transformer-based large language models and various combinations of traditional machine learning models with embeddings for stance classification.

This work is currently under review and the preprint is available on 
https://www.techrxiv.org/articles/preprint/GPT-4_as_a_Twitter_Data_Annotator_Unraveling_Its_Performance_on_a_Stance_Classification_Task/24143706

The original dataset annotated by 3 human coders can be found here. This full dataset contains 533 records with class labels 0, 1, and 2 representing against, favor, and none respectively. For this study, we only used a sample of this dataset containing 355 records with complete inter-rater reliability agreement among 3 human annotators. 
