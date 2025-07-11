# -English-Hindi-Neural-Machine-Translation

**Concise summary:**  
Built a 2-layer LSTM-based Seq2Seq model trained on 25,000+ English–Hindi TED sentence pairs. Achieved over 80% sentence-level translation accuracy through custom preprocessing, tokenization, padding, and teacher forcing. Enabled real-time inference with separate encoder–decoder models, without using attention mechanisms.

---

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)

---

## Installation
1. Clone the repository:  
   `git clone https://github.com/your-username/english-hindi-nmt.git`

2. Install dependencies:  
   `pip install -r requirements.txt`

3. Launch Jupyter and run the notebook:  
   `English_Hindi_NMT.ipynb`

---

## Usage
- Load and clean the Hindi–English TED corpus dataset.
- Preprocess the data with punctuation removal, tokenization, padding, and label shifting.
- Train the encoder–decoder LSTM model using Keras with teacher forcing.
- Use inference pipeline to translate unseen English sentences into Hindi.
- View sample translations and model outputs at various stages.

---

## Project Structure
english-hindi-nmt/  
├── English_Hindi_NMT.ipynb  
├── Hindi_English_Truncated_Corpus.csv  
├── requirements.txt  
└── README.md  

---

## Results
- Training dataset: 25,000 sentence pairs
- Translation accuracy: ~80–85% (qualitative)
- Enabled real-time sentence-level translation
- Separate inference models built for production testing
- Performance visualizations: loss curves and sample outputs
