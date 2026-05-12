# Sign Language Classification
We initially trained models locally using Jupyter notebook, however we ran into the challenge of hardware limitations. We transitioned to Google Colab using the T4 GPU.   

It's _**recommended to run the models on Google Colab for efficiency**_. To do this, simply open the "Sign_Language_Classification.ipynb" file.

If you would like to run this locally, follow the project set up instructions below.

## Local Project Setup Using Jupyter Notebook

Follow these steps to set up the project locally and start working with the Jupyter Notebook.

### First-Time Setup

**1. Clone the repository**
```bash
git clone https://github.com/lexinejazly-asuncion/Sign-Language-Classification.git](https://github.com/lexinejazly-asuncion/Sign-Language-Classification.git
cd Sign-Language-Classification
```

**2. Create a virtual environment**
```bash
python3 -m venv venv
```

**3. Activate the virtual environment**
```bash
source venv/bin/activate
```
*Note: You should now see `(venv)` in your terminal.*

**4. Install dependencies**
```bash
pip install -r requirements.txt
```

**6. Run Jupyter Notebook**
```bash
jupyter notebook
```
*Note: Open the link shown in your terminal (usually http://localhost:8888).*

---

## Subsequent Usage

After completing the initial setup, you only need to run these commands:

```bash
cd path/to/Sign-Language-Classification
source venv/bin/activate
jupyter notebook
```

---

## Saving Changes

To save and upload your work:

In jupyter: File -> Save All

In your terminal:

```bash
git status
git add .
git commit -m "Update project files"
git push
```
