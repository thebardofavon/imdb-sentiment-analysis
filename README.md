# imdb-sentiment-analysis
This is an application uses the [IMDB Movie dataset](https://www.kaggle.com/c/word2vec-nlp-tutorial/data?ref=hackernoon.com) from Kaggle to build a simple model that can classify if a movie review is positive or negative and is deployed using FastAPI.

## Running the app
To run the app locally, follow these steps:

1. Clone this repo
```sh
git clone git@github.com:thebardofavon/imdb-sentiment-analysis
```
2. Change into the directory and install the dependencies using the following command
```sh
npm install -r requirements.txt
```
3. Change the file paths according to your own system in main.py and app.py.
4. Run following command to run app.py
```sh
python app.py
````
5. Run the app:
```sh
uvicorn main:app --reload
```





