# Mastering the AI Toolkit: AI Tools Assignment

## Overview
This project demonstrates practical and theoretical mastery of key AI tools and frameworks, including PyTorch, Scikit-learn, and spaCy, through a series of tasks covering classical machine learning, deep learning, NLP, and ethical AI development. The project is organized for easy group collaboration and reproducibility.

## Project Structure
```
Sibia Week 3 AI assignment/
│
├── Part1_Theory/
│   └── Theoretical_Answers.md         # Answers to theory questions
│
├── Part2_Practical/
│   ├── Task1_Scikit_learn/
│   │   └── iris_classification.py     # Classical ML: Iris Decision Tree
│   ├── Task2_PyTorch/
│   │   └── mnist_cnn_pytorch.py      # Deep Learning: MNIST CNN (PyTorch)
│   └── Task3_spaCy/
│       └── review_analysis.py        # NLP: NER & Sentiment with spaCy
│
├── Part3_Ethics_Optimization/
│   ├── Ethics_and_Optimization.md    # Ethical reflection & optimization
│   ├── buggy_script.py              # Example of buggy DL code
│   └── fixed_script.py              # Fixed version of the above
│
├── Bonus_Deployment/
│   └── app.py                       # Streamlit web app for MNIST
│
├── mnist_cnn_pytorch.pth            # Saved PyTorch model for deployment
├── requirements.txt                  # All dependencies
└── README.md                         # This file
```

## Setup Instructions
1. **Clone the repository** and navigate to the project root.
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download spaCy model:**
   ```bash
   python -m spacy download en_core_web_sm
   ```
4. **Train the MNIST model (PyTorch):**
   ```bash
   python Part2_Practical/Task2_PyTorch/mnist_cnn_pytorch.py
   ```
   This will save `mnist_cnn_pytorch.pth` in your project root.

## Usage
- **Theory Answers:**
  - See `Part1_Theory/Theoretical_Answers.md` for detailed explanations.
- **Classical ML (Iris):**
  - Run: `python Part2_Practical/Task1_Scikit_learn/iris_classification.py`
- **NLP (spaCy):**
  - Run: `python Part2_Practical/Task3_spaCy/review_analysis.py`
- **Ethics & Debugging:**
  - See `Part3_Ethics_Optimization/Ethics_and_Optimization.md`
  - Try running `buggy_script.py` and then `fixed_script.py` to see error handling and solutions.
- **Web App (MNIST Demo):**
  - Launch with:
    ```bash
    python -m streamlit run Bonus_Deployment/app.py
    ```
  - Open the provided local URL in your browser, draw a digit, and see the model's prediction.

## Screenshots & Report
- Include screenshots of model outputs, accuracy graphs, and NER results in your final PDF report for submission.
- The report should also include ethical reflections and answers to all theory questions.

## Contribution & Collaboration
- This project is designed for group work (3-5 members).
- Use GitHub for version control and collaboration.
- Each member should contribute to both code and report.
- For the presentation, record a 3-minute video with all group members explaining your approach and results.

## Notes
- If you see warnings/errors related to Streamlit or PyTorch internals, they are safe to ignore as long as the app and scripts work.
- For any issues, consult the official docs for [PyTorch](https://pytorch.org/), [Scikit-learn](https://scikit-learn.org/), [spaCy](https://spacy.io/), and [Streamlit](https://docs.streamlit.io/).

## License
This project is for educational purposes as part of the "Mastering the AI Toolkit" assignment. 
