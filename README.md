# Cat-and-Dog-Image-Classifier

🐱 vs 🐶 Cat & Dog Classifier - My First Machine Learning Project!
📚 About This Project
This is my first Machine Learning project created during my college studies! I built this as part of the freeCodeCamp Machine Learning curriculum, spending extra time after my regular studies to learn about AI and Deep Learning.

As a Computer Science student, I wanted to understand how computers can "learn" to recognize images - just like how we learn to tell cats and dogs apart!

🎯 What I Learned
Core ML Concepts:
Neural Networks: Building a "brain" that learns patterns

Convolutional Layers: Teaching the computer to see edges, shapes, and features

Data Augmentation: Creating more training data from existing images

Transfer Learning: Using pre-trained knowledge (not used here, but learned about it!)

Python Skills:
TensorFlow 2.0 & Keras

Image processing with PIL

Data visualization with Matplotlib

NumPy for numerical computations

🧠 How My Model Works (Simple Explanation)
Imagine teaching a child to recognize cats vs dogs:

Step 1 - Show many pictures (Training)

Show 2000 cat pictures

Show 2000 dog pictures

Step 2 - Point out features (Convolutional Layers)

"Cats have pointy ears 👂"

"Dogs have floppy ears 🐕"

"Cats have different eye shapes 👀"

Step 3 - Practice (Validation)

Show new pictures to test learning

Correct mistakes

Step 4 - Final Test (Evaluation)

Show completely new pictures

See if it learned correctly!

📊 Results
Metric	Score
Training Accuracy	~95%
Validation Accuracy	~70%
Test Accuracy	>63% ✅
I achieved the freeCodeCamp requirement of 63% accuracy and even reached for the 70% extra credit!

🛠️ Technologies Used
https://img.shields.io/badge/Python-3.8-blue
https://img.shields.io/badge/TensorFlow-2.0-orange
https://img.shields.io/badge/Keras-DL-red
https://img.shields.io/badge/Jupyter-Notebook-green

Python 3.8+ - The programming language

TensorFlow 2.0 - Google's ML library

Keras - High-level neural networks API

Google Colab/Jupyter - Interactive development

Matplotlib - Creating visualizations

📁 Project Structure
text
cats-vs-dogs-classifier/
│
├── cats_vs_dogs.ipynb          # Main notebook with all code
├── README.md                    # This file
└── requirements.txt             # Python dependencies
🚀 How to Run
In Google Colab (Easiest)
https://colab.research.google.com/assets/colab-badge.svg

On Your Computer
bash
# Clone the repository
git clone https://github.com/Anshul39/rock-paper-scissors.git

# Install requirements
pip install tensorflow matplotlib numpy pillow

# Open Jupyter
jupyter notebook cats_vs_dogs.ipynb
💡 Key Insights I Learned
More data = better learning - That's why we augment images

Computers see differently - They see numbers, not pictures!

Patience is key - Training takes time (got a coffee break ☕)

Mistakes teach us - Low accuracy means we need to adjust

🎓 My Learning Journey
This project represents:

✅ 20+ hours of learning after college

✅ Understanding of neural networks

✅ First step into AI/ML

✅ freeCodeCamp certification progress

🔗 Connect With Me
GitHub: @Anshul39

LinkedIn: Anshul

Portfolio: [Your Website]

🙏 Acknowledgments
freeCodeCamp - For the amazing ML curriculum

My College Professors - For supporting my extra learning

TensorFlow Team - For the excellent documentation

📝 License
MIT License - Feel free to use this for learning!

⭐ If you're also learning ML, star this repo! We're in this together! ⭐

"The beautiful thing about learning is that no one can take it away from you." - B.B. King

📸 Sample Output
text
Epoch 20/20
📊 Training Accuracy: 95.2%
📊 Validation Accuracy: 71.3%
📊 Test Accuracy: 68.5% ✅

🎉 Successfully identified cats and dogs!
