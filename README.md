# First  Methology
## You Can Run the Jupyter Notebook to Summerize the Software Artifact Issues from the Point of View of a dweveloper
 It will first Download the List of the links of all the issues of the the link Provided bY THE USER 
 then 
 
We will Extract the Induvidal useful Components of the Git Isses 
They are The Title of the issue
Body of the issue 
Description of the issue
We will then store then in different files with names title body and Description
Then by using the hugging face transformers and langchain open api pipeline will summerize the induvidale summaries 
This Describes what the indeuvidal Title Says in the Similar way what is the key idea from the point of Developers in body and Description as well
We then Merge all the files and will summerize the entire Document and we also append the entire summery of the Document to new_Readme.md file


## While Handeling the Text Summerization Part

## ->As Hugging Facettransformers Was unable to handle the verylarge files of data then to solve thet issue we divide the the text files inti chunks of smaller size about 1000 tokens each then we summerize individual segment and then concitenate hte final Result

## -> Also Experomented with the vector word Embedding method and then summerizing the text The Accuracy (Summerizing Capeblity) of the Model is Resinabely low as we need the mode and the Avelabelity the Dataset to train the  model is Resinabely low so this Did’t came out to be veru grate idea












#Alternatively I also Explore new Methology to Summerize the entire Software artefact
# PyDocGen: Python  Generator
It makes the complete Summery for the python code which includes different types of Summery including code-summarizer, auto-generation of the requirements.txt file and the code visualization. 

``` bash
git clone https://github.com/sanskarbharti/Summery_generator
```

### Tech Stack used: Django, React, Python(including a various other python modules)

## Installation and Running Backend: 
### Django
To install Django and run Backend, follow the steps below:
1. Change the directory to django_bk:
``` bash
cd django_bk
```

2. Install the following packages
``` bash
pip install django django rest framework django-cors-headers openai networkx pipreqs pygithub pylint
```
3. Change the directory to django_test:
``` bash
cd django_test
```
4. Start the backend using the following commands:
``` bash
python manage.py runserver
```


## Installation and Running Frontend:
### React
To install React and run Frontend, follow the steps below:
1. Start another terminal in the Summery_Generator directory
2. Install all the dependencies with:
``` bash
npm install
```
3. Install the axios dependency in case not installed using the following command:
``` bash
pip install axios
```
4. Start the Frontend with the following command:
``` bash
