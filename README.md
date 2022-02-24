# 🦸 The Evolution of the Marvel Cinematic Universe 

## TL;DR
Check out `DNID Data Story.ipynb`!

## About the Project
Since its inception in 2008, the Marvel Cinematic Universe has become one of the largest movie franchises in the world, garnering a huge fan base and building an incredibly complex world throughout a single, cohesive narrative. My data story aims to capture how the MCU has changed over time from its first phase to its most recently completed phase: Phase Three. I use several datasets from [Kaggle](https://www.kaggle.com/) as specified below:
* [movies_metadata.csv](https://www.kaggle.com/rounakbanik/the-movies-dataset): "Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies."
* [credits.csv](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=credits.csv): "Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object."
* [mcu dataset.csv](https://www.kaggle.com/rachit239/mcu-complete-dataset): "The file contains 16 columns having information about all the movies in Marvel Cinematic Universe, up to phase 3. The data is scraped from IMDB official website as well as mojobox office."
* **missing_data.csv**: A dataset I created that contains cast and crew credits for any MCU movie within phases 1-3 that was not included in movies_metadata.csv.

Using the movie ids from `movies_metadata.csv`, I collected credits information from `credits.csv` and `missing_data.csv` to create network graphs showing how different narratives within the MCU intersect and bring together the universe over time. I also used various visualizations to show the progression of MCU grosses, movie ratings/metascores, actor appearances, and gender representation with each phase. 

Check out the data story in the `DNID Data Story.ipynb` file! Enjoy!❤️

## 💻 How to Run
Interested in running the Jupyter Notebook and exploring the data on your own?  

Download `DNID Data Story.ipynb` and a [zip file](https://drive.google.com/file/d/17vhSTGhGT3oxJGUKTI0keLG_7UOCSzSI/view?usp=sharing) of all the datasets I used. Ensure that all files are within the same folder before running the code.

## 🛠️ Built with
* Jupyter Notebook
* Python
* Matplotlib
* Numpy
* Pandas
* Seaborn
* Networkx
* WordCloud
