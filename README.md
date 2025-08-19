🖼️ REAL VS. AI-GENERATED IMAGE TEXTURES: A MACHINE LEARNING STUDY

This repository contains our project on distinguishing real images from AI-generated images using texture-based features and a variety of machine learning models. The work compares multiple classifiers and explores dimensionality reduction techniques to optimize performance.

📜 TABLE OF CONTENTS

1.Problem Statement
2. Dataset
3. Results & Key Insights
4. Conclusion
5. How to Use
6. Contributors

PROBLEM STATEMENT:

PROBLEM: 
The increasing realism of generative models like GANs and diffusion networks makes manual detection of AI images nearly impossible.

HYPOTHESIS: 
AI-generated images contains non-human textural artifacts that are not present in authentic photographs.

OBJECTIVE: 
To evaluate if machine learning classifiers can effectively distinguish Real vs. AI images using a feature set derived from texture analysis.

🧾 DATASET:

Source: Kaggle Dataset: Real vs AI-Generated Image Texture Feature Dataset

1. Size: 66,898 rows × 123 columns

2. Distribution:  33,477 Real images

3. 33,421 AI-generated images

4. Features: 122 float features + 1 label column


📊 RESULTS & KEY INSIGHTS:

1. Feature Selection:

Random Forest performed best → 81% accuracy.

2. Feature Extraction (PCA):

SVM (RBF kernel) performed best → 80.75% accuracy.

3. Logistic Regression, Naïve Bayes, and KNN showed moderate performance compared to Random Forest and SVM.

🎯 CONCLUSION

1. This study confirms that an image's textural properties are a strong indicator of its origin, making it an effective method for detecting AI-generated content.

2. Our findings show that dimensionality can be significantly reduced through both PCA and feature selection without a major loss in performance.

3. For this specific task, Random Forest and the RBF kernel SVM proved to be the most accurate and reliable classifiers.

🚀 HOW TO USE:
CLONE THE REPOSITORY:

Bash

git clone https://github.com/your-username/your-repository-name.git

Navigate to the project directory:

Bash

cd your-repository-name

Install the required dependencies:

Bash

pip install -r requirements.txt

Run the Jupyter notebook or Python scripts in the Code directory to see the implementation.

🧑‍💻 CONTRIBUTORS:

1. Shrutika Gupta

2. Puspita Biswas

3. Jaya Mary Jennifer D.

4. Agarwal Raj

5. Harsha K.






