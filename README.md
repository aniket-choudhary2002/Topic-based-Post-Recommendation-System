# Topic-based-Post-Recommendation-System

Report: Topic-based Post-Recommendation System

1. Introduction:

The objective of this project is to develop a functional topic-based post recommendation system using Generative AI. This report provides an overview of the methodology, including user and post profiling, and the evaluation metrics used to assess system performance.

2. Methodology:

2.1 User and Post Profiling:

To profile users, we tokenized and analyzed their posts using Generative AI models.
For post profiling, the same Generative AI models were utilized to understand the topics within each post.
User and post topics were extracted and used to create user-topic and post-topic matrices.

3. Recommendation Engine:

3.1 User-Post Matrix Creation:

User-topic and post-topic matrices were generated based on the topics identified during profiling.
Cosine similarity was employed to measure the similarity between user and post topics.
Top recommendations were obtained by selecting posts with the highest similarity to each user.

4. Evaluation Metrics:

Precision, recall, and F1 score were used as evaluation metrics to measure the accuracy and relevance of the system's recommendations.
Ground truth data was defined, and the system's predictions were compared against it to calculate the metrics.

5. Results:

The evaluation metrics indicated the system's effectiveness in providing accurate and relevant recommendations.
Further improvements and optimizations were identified for future iterations.

6. Code and Resources:

All code developed for the task, including user and post profiling, recommendation engine, and evaluation metrics, is provided in the attached code files.
Libraries such as scikit-learn, NumPy, and the Generative AI model library were utilized.

7. Demo:

A small screen recording has been included, showcasing the Topic-based Post Recommendation System in action. The demo illustrates how the system processes posts, profiles users, and generates recommendations.

8. Conclusion:

The developed system demonstrates the potential of Generative AI in creating an effective topic-based post recommendation system. The report concludes with reflections on the system's performance and areas for future enhancements.
