# Sentiment Trading System

An end-to-end NLP system that:
- Ingests financial news
- Applies transformer-based sentiment analysis
- Stores results in PostgreSQL
- Generates BUY/SELL/HOLD trading signals

## Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- PostgreSQL
- psycopg2

## Project Structure
sentiment-trading/
├── pipeline.py
├── data_ingestion.py
├── sentiment_model.py
├── signal_engine.py
├── db.py

## How to run
1. Create virtual environment
2. Install dependencies  
   pip install -r requirements.txt
3. Run pipeline  
   python pipeline.py

## Output
The system prints sentiment and trading signals and stores:
- raw news
- sentiment scores
- signals
in PostgreSQL.
