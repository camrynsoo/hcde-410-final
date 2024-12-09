# Books vs. Movies Adaptations: A Comparative Analysis of Ratings
HCDE410 - Assignment A7
Camryn Soo - 12/8/24

## Project Overview
In this project for my HCDE 410 Human Data Interaction class I explore the question, "Are books better than movies?" by comparing the popularity of books to their movie adaptations with their ratings. I use 3 different data sources to create a set that contains the information about books and their movie adaptations. I create a scatter plot to visually compare book and movie adaptations ratings. Then I check the statistical significance of if there is a difference between book and movie adaptations ratings using both a one sample t-test for the difference between ratings and a two sample-test for the comparison of their average ratings. Finally while the data in this scope shows there is a statistically difference between book and movie adaptations, I urge people to continue to consume media themselves to develop their own answer to the main question.

### Guiding Questions:
- **MAIN QUESTION: How does book popularity compare to their movie adaptations and see if there is an answer to this age old debate: are books better than movies?**
- How do at least 75 books compare to their movie adaptations according to their ratings?
- What percentage of time is a category (book vs. book adaptation) higher than the other?
- What is the average difference between a book release and its adaptation release?
- Consider edge cases and limitations of this work!


## Data Sources / Licenses
**Books ratings [(Kaggle by Abdallah Wagih Ibrahim - ](https://www.kaggle.com/abdallahwagih)["Books Dataset")](https://www.kaggle.com/datasets/abdallahwagih/books-dataset):** contains information about the book such as its publication date and its rating out of 5.

Credit:[Abdallah Wagih Ibrahim](https://www.kaggle.com/abdallahwagih)

License:[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) (therefore usable for this project!)

**List of books that have movie adaptations [(IMDb by Addicted-to-Films - ](https://www.imdb.com/user/ur3017944/?ref_=ls_usr_ov) ["Book-to-Film Adaptations")](https://www.imdb.com/list/ls000989358/?view=compact&sort=alpha%2Casc) and [(IMDb by kiraalt - ](https://www.imdb.com/user/ur3582225/?ref_=ls_usr_ov)["100 Movies based on 100 Classic Great Books")](https://www.imdb.com/list/ls074934904/):** Both of these lists are curated by individuals who have compiled a list of movies whose story originated from a book. They both include IMDb ratings out of 10.

Credit(s):[Addicted-to-Films](https://www.imdb.com/user/ur3017944/?ref_=ls_usr_ov) & [kiraalt](https://www.imdb.com/user/ur3582225/?ref_=ls_usr_ov)

License(s): Public domain


## Structure of "scaled_book_movie_data.csv" (the newly created dataset)
- Title (String): name of the book / movie adaptations
- IMDb Rating (Float): number from 0 to 10
- Book Rating (Float): number from 0 to 10
- Rating Difference (Float): number representing the difference between book and movie adaptations ratings. (+ = book ratings are higher, 0 = book and movie adaptations are the same, - = movie adaptations ratings are higher)
- Combined Average Rating (Float): this is the average of the book and movie adaptations ratings for the relevant title (I didn’t use in this project but thought it might be useful for future work)
- Delimiter style = a comma (,)


## Resources used
(coding and writing support)
- [Perplexity AI](https://www.perplexity.ai/)
- [ChatGPT](https://chatgpt.com/)
  
(background research)
- [Indiana University's libraries site covers the debate in a 2018 article](https://blogs.libraries.indiana.edu/mediabeat/2018/03/19/books-vs-movies-the-age-old-debate/)
- [Washington Post wrote a 2016 analysis](https://www.washingtonpost.com/news/wonk/wp/2016/01/05/the-book-really-is-better-than-the-movie/)
- ["Predicting Box Office Returns for Movies Adapted from Books"](https://saas.studentorg.berkeley.edu/rp/box-office).

(coding support)
-[GeeksForGeeks](https://www.geeksforgeeks.org/python-convert-list-of-dictionaries-to-list-of-lists/)
-[Plotly Scatter Plots](https://plotly.com/python/line-and-scatter/)

(analysis support)
-[TheDataScientist Website](https://thedatascientist.com/how-to-do-a-t-test-in-python/)


## Things presented for submission
- A Jupyter notebook 
- Runnable Data: "scaled_book_movie_data.csv"
- An MIT LICENSE
- Generated graphic: “HCDE_410_-_A7_Final_Scatter_Plot.png”
- A README
