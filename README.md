# Kaggle COVID-19 Prediction

## Topics Covered
  
## How to run
1. Build docker image
   
   `docker build -t kagglecovid-19 .`
2.  Run docker container

    `docker run -it -v $(pwd):/workdir -p 8888:8888 -t kagglecovid-19 bash`
3.  From inside the container workdir run to start jupyter notebooks

    `jupyter-notebook --ip='0.0.0.0' --port=8888 --no-browser --allow-root`

## Resources
- [Dataset](https://www.kaggle.com/c/19539/download-all)
