# Mack's Guestbook

Welcome to my guest book! Thanks for visiting.

## My Project

My project title is "Movie Gender Dialogue Analysis." You can visit my project repo [here](https://github.com/Data-Science-for-Linguists-2023/Movie-Gender-Dialogue-Analysis).

## Guestbook Notes

### Camryn

I really like your idea for the project and I think it will be really cool to explore. I am really interested in seeing how you plan to fill in the gaps, which is mentioned in your project plan. Furthermore, I thought your Data Object Creation file was very easy to read, and I like that you showed the dataframes and data relating to the dataframes a lot so that a reader can see whats going on. Sometimes its really easy to forget to show details like that, so it was really appreciated that those numbers were there!

In terms of improvement, I think your repository could benefit from a lot more organization and explanation. On the front page of your repository, it doesn't say anything, so someone viewing it has to explore and figure out where to go on their own. It would be helpful to explain in the README what aspects of your repository are and where they are located!

One thing I learned is that the data that you are working with is very extensive and a lot of the dataframes have columns in common, which will be really cool to see it all come together for data analysis purposes.

### Mack's response

Thank you for this! I took some time on the last progress report to get my landing page/read me in shape to help provide more clarification on my project and the repo layout.

### Ashley

- **Well Done:** I think it's great the way you dove into the data to check whether or not there were any missing values. This was something I encountered in my own data, where `.info()` indicated there were no NaN values, but this is because any missing values had been filled with another symbol (in your case, the ? symbol). This is difficult but critical to find, so great work for really looking closely at those values.

- **Suggestion:** Because you're going to be doing a lot of work joining this data into a more readable format, if it turns out you are able to publicly share all of your code, it might be helpful to include your final joined dataframe in your data samples as well as the original corpus data. If it's not publicly shareable, maybe just the first five lines would be helpful to show anyone looking at your project what the eventual final data you were using for most of your analysis looked like.

- **What I Learned:** It was interesting to learn just how large the timespan is of movies that this corpus covers - from 1927-2010! Over 80 years of movies will definitely give you a lot to work with if you choose to analyse changes in discourse over time.

### Mack's response

Thanks for the feedback! I finally solidified what can be shared so I have a copy of all of the data in my repo and will make my code and the data frames created completely open as well.

### Wilson

- **One thing I like:** I like the idea of your analysis a lot, and I think the end result will be really interesting to see.

- **One potential avenue for improvement:** It seems like you're in the middle of processing a bunch of different parts of your data and there's still not any possibility for analysis yet. Maybe it'd help to focus on a single aspect of your data at a time and get at least a few of those dataframes in a workable state to make sure that, if you're low on time, you can get at least some kind of analysis done? I'm not sure if you're really in danger of that or not, but just in case...

- **One thing I learned:** I didn't know NLTK had a names corpus -- I'm not sure how I would have approached figuring out what gender names are, but that names corpus seems super helpful.

### Mack's response
Thanks for your feedback! I have been able to get my data wrangled to a place where I have begun my analysis now. My largest hurdle was trying to get as many characters gender-coded as possible.

### Alex

- **One thing I like:** Your process cleaning and reorganizing your data is extrememly thorough and explained well. There doesn't seem to be much analysis yet, but with the amount of work you've done to collect you're data I you're on a really good path for addressing analysis later.

- **One potential avenue for improvement:** It would be nice to have some sort of statement in one of the notebooks lightly touching on some of the methods you plan on using during analysis to explain to readers why you are curating your data set in a specific way. It makes sense to focus in on the gender markers, since that's what the project is titled around, but overall it would be useful to get a clearer sense of how each DataFrame is connected to each other and what purpose they fulfill in your project. I think I understand how they're connected through IDs, but a blanket statement explaining it might be nice.

- **One thing I learned:** I was surprised to see how many more movies are from the 1990s in this corpus! I'd presume the number of movies produced in any given years had only increased over time. It makes me curious about how the original data set was collected.

### Mack's response
I appreciate your feedback! I definitely can do some more work on situating what is guiding my analysis on this project. I know I will incorporate it into my presentation and final report, but I will look into adding it to some other documentation to help everything be more clear.


### Varun

- **One thing I like:** I really like the readme and structure to the repo, it's really organized and nice!

- **One potential avenue for improvement:** Maybe some "mission statement" on what you hope to find? The analysis is super good but I want to know what you're thinking and what you might expect to find.

- **One thing I learned:** I actually didn't know about this dataset. Looks super cool!

### Mack's response
Thanks for the feedback! I definitely can include some sort of hypotheses/mission statement. I can clarify what is guiding me in my work.


### Soobin

- **One thing I like:**
I know you struggled with the question mark in the `gender` column, and I am so glad that you made improvement! I can see that you put A LOT of effort on processing that information. + `discourse_df` data set looks super clean and squeakyyyy
I also like how you explained every step you made. All the comments were helpful and walked me through your project.

- **One potential avenue for improvement:**
In my opinion, for your analysis, looking at the sentence level might be a little hard to grasp what is going on because they are super short. Grouping the sentences by the movie ID (or character ID) and then grouping them by decade could give you a bigger picture and tendency.

- **One thing I learned:**
I forgot about `pickle` package. I might use pickle in my project as you did. (pickling the clean data, making new file, and using the pickled data so that I don't have to process the data everytime I open it!)
I am excited to see your result, especially regarding the hedging words as a person who (kind of) always uses them. (and I just used it again lol)


### Mack's response
Thanks Soobin! You bring up a great point! I think grouping by character could be really revealing and add another way to analyze the data. I am going to group by decade, but some other ways of grouping the data should be beneficial.
