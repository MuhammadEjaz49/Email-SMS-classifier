Email/SMS Spam Classifier
-------------------------------------------

Contents:
- app.py            : Streamlit app
- model.pkl         : Pretrained demo MultinomialNB model
- vectorizer.pkl    : TF-IDF vectorizer used with the model
- requirements.txt  : Python dependencies (compatible with Python 3.12)
 
How to run (local machine):
1. Extract the ZIP folder.
2. Create and activate a Python 3.12 virtual environment (recommended):
   python -m venv venv
   # On macOS/Linux:
   source venv/bin/activate
   # On Windows:
   venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt
4. Run the Streamlit app:
   streamlit run app.py
5. The app will open at http://localhost:8501

