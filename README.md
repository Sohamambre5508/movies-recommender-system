# movies-recommender-system


![Python](https://img.shields.io/badge/Python-3.10-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Streamlit-red)
![API](https://img.shields.io/badge/API-TMDB-fcba03)


This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.
using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `requests`.

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/The-Movie-Cinema/blob/master/requirements.txt) file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY at line no. 2 of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

# Screenshot

![image](https://github.com/Sohamambre5508/movies-recommender-system/assets/121428299/2abc732c-b40c-41a2-be10-57ca3da2313b)

![screen1](https://github.com/Sohamambre5508/movies-recommender-system/assets/121428299/efab7ebb-f466-401c-9c01-17cf58a74693)



https://github.com/Sohamambre5508/movies-recommender-system/assets/121428299/2382f7d1-8ea7-4253-b7ca-02a0bb76474c





### Sources of the datasets 

 [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
