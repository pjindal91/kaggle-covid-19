# Kaggle COVID-19 Prediction
## [View Notebook](https://nbviewer.jupyter.org/github/pjindal91/kaggle-covid-19/blob/master/covid-19.ipynb)

## Topics Covered
- **CatBoost** algorithm for regression
- **Feature Engineering** - add new features using the existing data to boost the training data
- Encoding **Categorical Data**
- Handling **time series** data
- **Plotly** maps
  
## How to run
1. Build docker image
   
   `docker build -t kagglecovid-19 .`
2.  Run docker container

    `docker run -it -v $(pwd):/workdir -p 8888:8888 -t kagglecovid-19 bash`
3.  From inside the container workdir run to start jupyter notebooks

    `jupyter-notebook --ip='0.0.0.0' --port=8888 --no-browser --allow-root`

## Resources
- [Dataset](https://www.kaggle.com/c/19539/download-all)
