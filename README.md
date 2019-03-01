# rotten-tomatoes
Scrape data with BeautifulSoup from rottentomatoes.com

Based on a data gathering task at udacity.com, I try to practice data scraping skills with BeautifulSoup.<br>
I used html files of the 100 best rated movies, and use jupyter notebook to create a dataframe, what finally should contain the following information of these films:
* Movie title (retrieved on 2019-02-23)
* Genre (retrieved on 2019-02-23)
* Director (retrieved on 2019-02-24)
* runtime (mins) (retrieved on 2019-02-24)

The html and ipynd files represent the status of this project. On 2019-02-26, I created the data frame with the above described information. 

On 2019-02-27, I got the idea that I can also scrape data directly from the page rottentomatoes.com, this section is quiet interesting in this regard： [Top 100 Movies of 2018](https://www.rottentomatoes.com/top/bestofrt/?year=2018)

2019-02-28: At first I will create a list of links to these 100 movies.

2019-03-01: I opened another branch (direct-scrape) in this repo to try out a direct scrape from the internet

2019-03-01: I uploaded ipynd and html documents: first step: get access to the content of [Top 100 Movies of 2018](https://www.rottentomatoes.com/top/bestofrt/?year=2018) 
