## Phishing_URL_Iteration_2
### File Architecture ###


- [app.py](./app.py)
- [catboost_info](./catboost_info)
  - [catboost_training.json](./catboost_info/catboost_training.json)
  - [learn](./catboost_info/learn)
    - [events.out.tfevents](./catboost_info/learn/events.out.tfevents)
  - [learn_error.tsv](./catboost_info/learn_error.tsv)
  - [time_left.tsv](./catboost_info/time_left.tsv)
  - [tmp](./catboost_info/tmp)
- [feature.py](./feature.py)
- [phishing.csv](./phishing.csv)
- [Phishing URL Detection.ipynb](./Phishing%20URL%20Detection.ipynb)
- [pickle](./pickle)
  - [model.pkl](./pickle/model.pkl)
- [Procfile](./Procfile)
- [__pycache__](./__pycache__)
  - [feature.cpython-3XX.pyc](./__pycache__/feature.cpython-3XX.pyc)  # Note: Update the Python version
- [requirements.txt](./requirements.txt)
- [static](./static)
  - [styles.css](./static/styles.css)



         
    
### Execution ###
> pip install -r requirements.txt
> 
> run Phishing URL Detection.ipynb #for model
>  
> python app.py

Visit http://127.0.0.1:5000/ in your browser.


