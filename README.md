# Week-III-AI-Tools-Assignment
# AI Specialization - Week III

This repository contains completed scripts, notebooks, and resources for **Week III** of the AI Specialization course.

## Contents

- `cnn_model.py` & `cnn_model.ipynb`: Implementation and demonstration of a Convolutional Neural Network (CNN) for image classification tasks.
- `decision_tree_classification.py` & `decision_tree_classification.ipynb`: Scripts and notebooks for Decision Tree classification using the Iris dataset.
- `iris.csv`: The Iris dataset used for classification tasks.
- `ethics&optimisation.txt`: Notes and discussion on ethical considerations and optimization techniques in AI.
- `theory.pdf`: Supplementary theoretical material for the week.

## Getting Started

1. Clone the repository:
    ```bash
    git clone <https://github.com/agu803eh/Week-III-AI-Tools-Assignment.git>
    ```
2. Navigate to the project directory:
    ```bash
    cd "AI-Specialization/Week III"
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

- To run Python scripts:
  ```bash
  python cnn_model.py
  python decision_tree_classification.py
  ```
- To explore and run notebooks:
  ```bash
  jupyter notebook cnn_model.ipynb
  jupyter notebook decision_tree_classification.ipynb
  ```
- Review `ethics&optimisation.txt` and `theory.pdf` for additional context and theoretical background.

## Notes

- The Iris dataset (`iris.csv`) is required for the classification scripts and notebooks.
- Each notebook provides step-by-step explanations and results.

## License

This project is for educational purposes.

## Summary of Workflows

- **Preprocessing:** Data cleaning and normalization are performed on the Iris dataset to prepare it for modeling. For image data, resizing and augmentation techniques are applied in the CNN workflow.
- **Modeling:** Two main models are implemented: a Convolutional Neural Network (CNN) for image classification and a Decision Tree for tabular data classification.
- **Training:** Both models are trained on their respective datasets with appropriate hyperparameters. Training progress and metrics are logged for analysis.
- **Testing & Evaluation:** After training, models are evaluated on test data. Metrics such as accuracy, precision, recall, and confusion matrices are used to assess performance.
- **Visualization:** Training history (loss and accuracy curves), decision boundaries, and confusion matrices are visualized within the notebooks to aid interpretation and model assessment.

For detailed code and results, refer to the provided scripts and notebooks.
