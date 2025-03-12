# NER System with FastAPI Deployment

[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68-green.svg)](https://fastapi.tiangolo.com/)
[![Docker](https://img.shields.io/badge/docker-20.10-blue.svg)](https://www.docker.com/)

Named Entity Recognition system with production-ready API deployment

## Features
- spaCy-based NER model (F1: 0.86)
- FastAPI endpoint with rate limiting
- Docker containerization
- Basic authentication
- Batch processing support

## Installation
```bash
# Clone repository
git clone https://github.com/yourusername/ner-submission.git
cd ner-submission

# Install dependencies
pip install -r app/requirements.txt
pip install -r training/requirements.txt --extra-index-url https://download.pytorch.org/whl/cu113
