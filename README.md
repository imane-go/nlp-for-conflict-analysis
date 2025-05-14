# NLP for Conflict Analysis

This project explores the use of Natural Language Processing (NLP) techniques, particularly TF-IDF and BERT, to analyze and understand YouTube comments related to the Gaza-Israel conflict. The goal is to gain insights from large volumes of user-generated content on social media platforms and apply NLP methods to uncover patterns, sentiments, and significant discussions surrounding the topic.

## Project Structure

The project is organized as follows:

<p>nlp-for-conflict-analysis/<br>
<ol> 
├── data/ # Contains datasets (raw and processed)
│ ├──  raw/ # Raw data (e.g., comments CSVs)
└── processed/ # Processed data ready for analysis 
│
├── notebooks/ # Jupyter notebooks for exploration and analysis</ol>
│
├── src/ # Python scripts for preprocessing and analysis<br>
│ ├── data_preprocessing.py # Data cleaning and preparation<br>
│ ├── tfidf_analysis.py # TF-IDF vectorization and analysis<br>
│ └── bert_analysis.py # BERT-based analysis (to be added later)<br>
│
├── outputs/ # Results and outputs<br>
│ ├── figures/ # Figures generated during analysis<br>
│ └── reports/ # Generated reports from analysis<br>
│
└── README.md # Project documentation (this file)</p>

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Ensure that you have the following installed:

- Python 3.x
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/imane-go/nlp-for-conflict-analysis.git
   
2. Navigate to the project directory:
   ```bash
   cd nlp-for-conflict-analysis
3. Set up a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
4. Install the required dependencies:
```bash
pip install -r requirements.txt
