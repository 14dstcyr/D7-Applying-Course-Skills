# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

•	Go to Dr. Case’s repo, use the “Use This Template” button to create a new repo for myself.
•	I went into my new repo, and in there I went to the green code button and clicked on the down arrow. 
    I clicked on the copy icon (to copy url to clipboard).
•	Opened VS Code, Clicked on cntl+shift+P to open the bar at the top, selected “Git: Clone”, 
    selected where I wanted the repo to be stored on my computer (select as repository destination).
•	VS Code shows a box that asks if you want to open the cloned repository, click open.
•	Click on the file with the .ipynb ending.
•	Go into the root and added the requirements.txt to it.
•	Add the following to the requirements.txt: 
    o	requests
    o	spacy
    o	spacytextblob
    o	jupyter
    o	matplotlib
    o	numpy
    o	Beautifulsoup4

** Go into GitBash (if you are in VS Code) and install the following:
    •	$ python -m venv .env
    •	$ .env/Scripts/activate
    •	$ pip install -U pip setuptools wheel
    •	$ pip install -U spacy
    •	$ python -m spacy download en_core_web_sm
    •	$ pip install -r requirements.txt
    •	$ pip install spacytextblob
    •	$ pip install html5lib


** In a code cell in Jupyter Notebook, run the following code to install Requests:
    !pip install requests


## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
