# agents

1. Install Pytjong 3.10 or later 
2. Create and activate a virtual environment:
	* python -m venv venv
	* source venv/bin/activate     # On Windows: venv\Scripts\activate
3. Create a new file named requirements.txt and copy the code provided at the end of this section.

Install all required libraries:

pip install -r requirements.txt
(Optional) Link this environment to your IDE or Jupyter notebook:

python -m ipykernel install --user --name=venv
After that, you’ll be ready to explore the ungraded labs locally 🚀

📄 Content for requirements.txt
# === Agent + LLM Tools ===
aisuite==0.1.11
anthropic
docstring-parser
markdown
mistralai
openai
qrcode
tavily-python>=0.7.12
textstat
vertexai

# === Web Framework + API ===
fastapi
pydantic
pydantic[email]
python-dotenv
python-multipart
requests
sqlalchemy
uvicorn

# === Notebook Experience ===
ipywidgets
jupyter_server
nbclassic
notebook

# === Data Analysis / Display (Optional Enhancements) ===
duckdb
matplotlib
pandas
seaborn
tabulate
tinydb

# === Machine Learning / NLP (Optional Enhancements) ===
jinja2
psycopg2-binary
scikit-learn
Wikipedia
