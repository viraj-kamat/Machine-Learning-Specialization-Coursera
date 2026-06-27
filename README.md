# Machine Learning Specialization — Andrew Ng (DeepLearning.AI / Stanford)

This repo contains my completed coursework, lecture slides, and lab notebooks from the **Machine Learning Specialization** by Andrew Ng, offered through DeepLearning.AI and Stanford Online on Coursera.

🔗 **Course link:** [Machine Learning Specialization on Coursera](https://www.coursera.org/specializations/machine-learning-introduction)

✅ **Status:** Completed — all 3 courses, certificates received.

## 📚 Courses Covered

1. **[Supervised Machine Learning: Regression and Classification](https://www.coursera.org/learn/machine-learning)**
   - Linear regression, logistic regression, gradient descent, cost functions, regularization
2. **[Advanced Learning Algorithms](https://www.coursera.org/learn/advanced-learning-algorithms)**
   - Neural networks, forward/backpropagation, TensorFlow/Keras, decision trees, ensemble methods (random forests, boosting)
3. **[Unsupervised Learning, Recommenders, Reinforcement Learning](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning)**
   - K-means, anomaly detection, collaborative filtering, content-based recommenders, deep reinforcement learning (MDPs, Bellman equations, Q-learning, DQN with replay buffer, ε-greedy decay, soft updates)

## 📁 Repo Structure

Each course has its own top-level folder, containing a `PDFs` folder (slide decks) and an `NBs` folder (lab notebooks, organized by week):

```
.
├── Course_1/                          # Supervised Machine Learning - Regression and Classification
│   ├── MLS_C1_PDFs/                   # All lecture slide PDFs for the course
│   └── MLS_C1_NBs/
│       ├── Week_1/                    # Zipped lab workspace(s) for Week 1
│       ├── Week_2/
│       └── Week_3/
├── Course_2/                          # Advanced Learning Algorithms
│   ├── MLS_C2_PDFs/
│   └── MLS_C2_NBs/
│       ├── Week_1/
│       ├── Week_2/
│       └── Week_3/
├── Course_3/                          # Unsupervised Learning, Recommenders, Reinforcement Learning
│   ├── MLS_C3_PDFs/
│   └── MLS_C3_NBs/
│       ├── Week_1/
│       ├── Week_2/
│       └── Week_3/
└── README.md
```

- **`MLS_Cx_PDFs/`** — PDF exports of the official lecture slides for that course, kept at the root of the PDFs folder.
- **`MLS_Cx_NBs/Week_n/`** — Zipped lab workspaces (one zip per lab) for that week, as downloaded from the Coursera/Jupyter environment — includes notebooks, datasets, and helper scripts.

## 🚀 Usage

To run a lab locally:

```bash
# Unzip a specific lab workspace
unzip Course_1/MLS_C1_NBs/Week_1/<lab-name>.zip -d Course_1/MLS_C1_NBs/Week_1/<lab-name>

# Move into the folder
cd Course_1/MLS_C1_NBs/Week_1/<lab-name>

# (Optional) create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies (if a requirements file is included)
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 🛠️ Tools & Frameworks

- Python, NumPy, scikit-learn
- TensorFlow / Keras
- Jupyter Notebooks

## 📜 Certificate

Certificates of completion for all three courses were issued upon finishing the specialization.

## 📝 Notes

This repo is for personal reference and portfolio purposes. Course materials (slides, datasets, starter code) belong to DeepLearning.AI / Stanford Online / Coursera — included here for personal learning records only, not for redistribution.
