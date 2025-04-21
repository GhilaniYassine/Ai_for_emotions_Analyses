# AI Emotion Analysis Project

This project, developed during an intensive hackathon by our passionate team, demonstrates the power of Large Language Models (LLMs) in emotional intelligence. As LLM enthusiasts, we leveraged the Gemini AI model to create a sophisticated emotion analysis system.

## Project Overview

The system is divided into two main components:
1. A FastAPI-based REST API for real-time emotion analysis
2. A Jupyter notebook for batch analysis and visualization

## Hackathon Context

This solution was developed as part of a hackathon challenge, where our team aimed to push the boundaries of emotion analysis using cutting-edge AI technology. Our love for LLMs drove us to create an innovative solution that combines the power of Gemini AI with practical applications.

## Components

### Emotion Analysis API

Located in `/emotion-analysis-api/`, this is a FastAPI application that:
- Processes text input for emotional content
- Uses Google's Gemini AI model for analysis
- Detects 21 different emotions including:
  - Negative: Anxiety, Stress, Anger, Sadness, Fear, etc.
  - Positive: Joy, Hope, Gratitude, Pride, etc.
  - Neutral: Curiosity, Acceptance, Ambivalence

### Analysis Notebook

Located in `analyse.ipynb`, this notebook provides:
- Batch processing capabilities
- Visualization of emotional patterns
- Results stored in `plots_1session/` and `plots_entire/` directories

## Installation

1. Clone the repository
2. Install API dependencies:
```bash
cd emotion-analysis-api
pip install -r requirements.txt
```

## Usage

### Running the API

```bash
cd emotion-analysis-api
uvicorn src.main:app --reload
```

The API will be available at `http://127.0.0.1:8000`

## Why We Love LLMs

Our team's passion for Large Language Models drove this project's innovation. LLMs like Gemini AI represent the future of human-computer interaction, enabling nuanced understanding of human emotions that was previously impossible. This project showcases just a fraction of what's possible with these amazing tools.

## License

This project is licensed under the MIT License.