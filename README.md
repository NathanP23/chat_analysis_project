# Chat Analysis Project

This project analyzes chat transcripts to extract psychological cues, emotional trends, and relational dynamics using numerical data and qualitative analysis.

## Installation

```bash
pip install -r requirements.txt
python main.py data/chat_file.txt
```
## Structure
```bash
chat_analysis_project/
│
├── data/                              # Folder for storing input chat files and processed output
│   ├── chat_file.txt                  # Input chat transcript (placeholder)
│   └── output/                        # Folder for storing generated reports and graphs
│       ├── report.pdf                 # Sample report output
│       ├── sentiment_graph.png        # Sample sentiment graph
│       └── word_cloud.png             # Sample word cloud output
│
├── src/                               # Main source folder for all project code
│   ├── main.py                        # Main script for loading and processing chat files
│   ├── sentiment_analysis.py          # Module for sentiment analysis
│   ├── psychological_cues.py          # Module for psychological cue extraction
│   ├── conversation_dynamics.py       # Module for analyzing conversation dynamics
│   ├── visualization.py               # Module for graphical analysis and visualizations
│   ├── report_generation.py           # Module for report generation
│   └── utils.py                       # Utility functions for file I/O and chunking
│
├── tests/                             # Unit tests for each module
│   ├── test_sentiment_analysis.py     # Tests for sentiment analysis module
│   ├── test_psychological_cues.py     # Tests for psychological cue extraction module
│   ├── test_conversation_dynamics.py  # Tests for conversation dynamics module
│   └── test_utils.py                  # Tests for utility functions
│
├── config.yaml                        # Configuration file for parameters (chunk size, thresholds, etc.)
├── requirements.txt                   # Python packages required for the project
├── README.md                          # Documentation for project overview and instructions
└── LICENSE                            # License file (optional)
```