### Team Ditto: Alice Liu, Emily Kim, Lily Liang
![](https://github.com/AliceLiu17/csc448_final/blob/main/readme_pic.jpg)
----

#### Libraries used
- Pandas
- NumPy
- Matplotlib
- NLTK
- Stopwords
- TfidfVectorizer
- Scikit-learn 
- Seaborn 
- ipywidgets
- Voilà Jupyter server extension

----

#### Tasks

| Task    | Assigned |
|---------|-----|
| Create Github Repository  | Everyone  |
| Brainstorm Project    | Everyone  |
| Finding Dataset    | Everyone  |
| Combine data and removing duplication    | Everyone  |
| EDA    | Everyone  |
| Data Preprocessing    | Everyone  |
| Modeling: Gradient Boosting, random forest    | Alice  |
| Modeling: SVM, logisitc regression    | Emily  |
| Modeling: Naive bayes, decision tree    | Lily  |
| Model Evaluation    | Alice, Lily  |
| Create User Interface    | Lily, Emily  |

**Everyone = each person in the team tries it on their own file and we come together through zoom to discuss, combine, and make decisions**

**Everyone contributed and helped in each of the task**

----

#### Voila Implementation:
[Watch Screen Recording](https://github.com/AliceLiu17/csc448_final/raw/main/voila_recording.mov)

<video width="320" height="240" controls>
    <source src="https://github.com/AliceLiu17/csc448_final/raw/main/voila_recording.mov" type="video/mp4">
    Your browser does not support the video tag.
</video>


**SPAM:** 
1. click here to get your reward
2. CliCK Here: VerIFy

**NOT SPAM:**
1. Hi bestie, how are you
2. Going to costco

----

#### Setup:
1. Download and install [Anaconda](https://www.anaconda.com/download)
2. Launch a jupyter notebook
3. Mac users, open up terminal and type in `jupyter notebook`
4. Window users, open up your Anaconda Power Shell (in the Ananconda Folder you can find in your home menu), and type in `jupyter notebook`

----

#### Running our Program:
1. Download the github zip 
2. Open the files in jupyter notebook
3. On the top menu, press cell → run all to run our notebooks

----

#### Prototype:
1. Open Voila Implementation notebook
2. You need these extensions to install so make a new cell above the first cell and run these commands: `!pip install ipywidgets==8.0.4`, `jupyter nbextension enable --py widgetsnbextension` and `!pip install voila`
3. Note after installing you must reopen jupyter notebook and there will be a Voila button under help
4. If there are any questions, please follow this [article](https://towardsdatascience.com/4-python-packages-to-create-interactive-dashboards-d50861d1117e) specifically the first two packages

----

#### Resources:
1. **[First Dataset](https://www.kaggle.com/datasets/mfaisalqureshi/spam-email)** 
    - 2 columns, 5k rows
    - Columns: spam/not spam, message
    - Possible strategy: NLP, removing stopper words, analyze word frequency
  
2.  **[Second Dataset](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset/data)** 
    - 2 columns, 3k rows
    - Columns: spam/not spam, message
