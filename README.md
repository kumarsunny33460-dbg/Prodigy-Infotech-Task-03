📖 Text Generation with Markov Chains

🔹 Overview

This project implements a Markov Chain-based Text Generator that generates new text sequences at both the word-level and character-level.
It builds a statistical model from input text and predicts the next word/character based on probability distribution.

🔹 Features

✅ Word-level text generation (sentences using words)

✅ Character-level text generation (sequences letter by letter)

✅ Configurable n-grams (bigrams, trigrams, etc.)

✅ Randomized unique outputs every run

✅ Simple and modular Python design

🔹 Requirements

Python 3.x

No external libraries required (uses only built-in libraries: random, re, collections)

🔹 How to Run

Clone this repository:

git clone https://github.com/your-username/Prodigy-Infotech-Task-03.git
cd Prodigy-Infotech-Task-03


Run the script:

python markov_text_generator.py

Example Usage
# Word-level Markov Chain
word_gen = MarkovChainTextGenerator(mode="word", n=2)
word_gen.train(sample_text)
print(word_gen.generate(length=30))

# Character-level Markov Chain
char_gen = MarkovChainTextGenerator(mode="char", n=3)
char_gen.train(sample_text)
print(char_gen.generate(length=200))

🔹 Example Output

Word-level Example:

artificial intelligence is the future of technology machine learning and deep learning are subsets of ai markov chains are used for text generation


Character-level Example:

artificial intellignce is th futue of tecnoogy. marov cains ae usd fr tet genration in natur lague procssing...

🔹 Applications

🤖 Chatbots – conversational text generation

✍️ Creative writing – poetry, stories, lyrics

💬 Auto-suggestions – predictive typing

📚 NLP research – foundational concept in language modeling

🔹 File Structure
📂 Prodigy-Infotech-Task-03
 ├── markov_text_generator.py   # Main Python code
 ├── README.md                  # Project documentation
 └── Report.pdf                 # Detailed internship task report

🔹 Author

👨‍💻 Sunny Kumar
B.Tech CSE (2nd Year) | Intern @ Prodigy InfoTech

📌 This repository is part of my internship tasks at Prodigy Infotech.
