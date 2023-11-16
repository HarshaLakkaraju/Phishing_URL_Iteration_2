## Phishing_URL_Iteration_2
### File Architecture ###

.
├── app.py                
├── catboost_info        
│   ├── catboost_training.json                        
│   ├── learn            
│   │   └── events.out.tfevents        
│   ├── learn_error.tsv        
│   ├── time_left.tsv        
│   └── tmp        
├── feature.py        
├── phishing.csv        
├── Phishing URL Detection.ipynb        
├── pickle        
│   └── model.pkl        
├── Procfile        
├── __pycache__        
│   └── feature.cpython-311.pyc        
├── requirements.txt            
└── static            
    └── styles.css            
    
### Execution ###
> pip install -r requirements.txt
> 
> run Phishing URL Detection.ipynb #for model
>  
> python app.py
url:http://127.0.0.1:5000/
