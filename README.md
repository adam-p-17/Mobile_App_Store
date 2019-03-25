# Mobile App Rate Classifier

The main purpose of the project is to classify mobile app into correct rating category basing on app description and other provided features. 
The idea to obtain good results is to create various statistical models and compare the accuracy score. 

## Run notebook

Project was written in python 3.7. All required packages are included in requirements.txt.

```bash
cd <main dir>
virtualenv -p python3.7 venv
source venv\bin\activate
pip install -r requirements.txt
deactivate
```

### Cloud VM

Project was execuded in Google Cloud Platform - Google DataLab. 
If you are curious how to use DataLab folow this [instruction](https://cloud.google.com/datalab/docs/quickstart)

#Important

Visualisations were created in plotly. Github does not support embedded HTML/JavaScript. To see all plots please go [here](https://nbviewer.jupyter.org/github/adam-p-17/Mobile_App_Store/blob/master/Mobile%20App%20Rate%20Classifier.ipynb)
