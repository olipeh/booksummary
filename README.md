# Book Summary RAG System

A RAG (Retrieval-Augmented Generation) system for generating book summaries using Streamlit and advanced testing practices.

## Project Structure

```plaintext
rag_testing_exercise/
├── data/               # Data files directory
├── src/               # Source code
├── tests/             # Test files
├── exercises/         # Testing exercises
├── deploy/            # Deployment configuration
└── docs/             # Documentation
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/olipeh/booksummary.git
cd booksummary
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Copy `.env.example` to `.env` and configure your environment variables:
```bash
cp .env.example .env
```

## Development

- Main application: `src/app.py`
- Run tests: `python -m pytest tests/`
- Build application: `python build_app.py`
- Deploy: `python deploy.py`

## Testing Exercises

See the `exercises/` directory for structured testing exercises:
1. Basic Testing (`exercise_1_basic_testing.md`)
2. Edge Cases (`exercise_2_edge_cases.md`)
3. Metrics (`exercise_3_metrics.md`)

## License

MIT License