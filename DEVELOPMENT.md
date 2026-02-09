# Developing Kantanji

To clone the repository, it's best to do this to avoid downloading all assets:

```
git clone -b development https://github.com/KanjiBase/KanTanJi.git
```

Then, you can run against test data by:

````bash
python -m venv .venv
# activate: .venv\Scripts\activate for windows, .venv/bin/activate unix
python install -r requirements.txt
python main.py
````

You might need to download pdfkit binaries (`wkhtmltopdf`) [for pdfkit library first](https://pypi.org/project/pdfkit/). 
The output generates ``.test`` assets and `.TEST-README.md`.
