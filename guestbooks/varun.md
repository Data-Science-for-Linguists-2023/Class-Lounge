# Varun's Guestbook
You can find the repository here: [Text-Based-Age-Recognition](https://github.com/Data-Science-for-Linguists-2023/Text-Based-Age-Recognition)

# Note
hey!

## Soobin

* One thing I think is done well
I like how you organized data succintly. You well prepared your data for the feature engineering. I am excited to see your next move! 

* One suggestion
I think it might improve the result if you divide the age group a little differently. I am not sure which age is the youngest in your dataset, but it seems like 13 is the youngest. (I am saying this based on your plot.) You set the bin for the age group as 10, 19, 29, 39, and if 13 is the youngest, there could be a problem because people who is between 13-19 would fall into 10s, while 20-29 would fall into 20s. Same applied for the 40s group if the oldest age is 48.
Also, you removed `id` column. Seems like there are more than one blog written by one person, and if you remove id value, the result could be a little skewed? 
Well, there are more than enough data for younger generations, but for the blogs written by 40s, it would be a little tricky to interpret whether it is truly the characteristic of 40s or if it's just one (or two) person's writing habit.

* One thing I learned
I like your plot about age distribution! I didnt know that I can sort the x-axis based on each value, and now I know thanks to you. Also, you used f-string, which I have no knowledge of. seems like it's quite convenient.

* One random comment about the data
I like that it has `sign` column!! I don't know much about zodiac signs and the salient characteristics of each of them, but it would be really fun to check if those stereotypes are true based on the text I guess?!

## Seth

* One thing you did well

Your repository is really interesting! Using Python scripts instead of the often tedious to set up Jupyter Notebook is clever. You also handle multiple different types of data (pulled from Reddit + text files for the blog data), which is impressive!

* One avenue for improvement

Great job on the content of your repository! One suggestion I have is creating a 'roadmap' within your repo that can guide users in exploring your data/analysis, as I found the number of files a bit overwhelming. 

* One thing I learned

Your 'distribution of bloggers by age' graph is super cool! It's interesting to see the jump from 13 to 33, from which it never comes back down. 

## Sen

- Your coding in the jupyter notebooks seems really succint and efficient. It seems that you've given a lot of thought to the types of features that could affect your question, given that you have scripts analyzing both lexical and syntactic features. I'm looking forward to seeing the results of your analysis.

- I like how you've organized your repository but I did find myself searching and clicking around a lot, so maybe including some type of directory in your README.md or links in your progress report and/or between jupyter notebooks and scripts and such would make it a bit easier to navigate.

- I'm used to just throwing all of my code into a jupyter notebook, so it was cool to learn about creating and utilizing Python scripts instead.

## Camryn

1. Your notebook demonstrates a high level of skill and a lot of thought regarding the various stages of collection and analysis. I really liked your use of scripts within your project as well.

2. I think your repository could benefit from some more comments and documentation. I wasn't sure where to begin with looking at your repository, so maybe adding some type of order to your README or at the top of your notebooks. Some parts of your notebook are without any explanation, so it would be beneficial to add some more comments or have a summary section at the end of your notebooks summarizing your results.

3. The work you did in process_reddit_dataset.ipynb is really interesting, and I definitely learned some stuff about processing the Reddit data. For example, your work to remove mod posts was a good point that I did not think of when parsing my own Reddit data.