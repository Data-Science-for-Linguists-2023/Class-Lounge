# Ashley's Guestbook

Thanks for checking out my guestbook! Any feedback is greatly appreciated.

##  [What's the Story?: Linguistic Variation in Goodreads Reviews by Genre](https://github.com/Data-Science-for-Linguists-2023/Goodreads-Genre-Reviews-Analysis)

For my project, I am curious to see if the written language style used by readers differs depending on the genre of book they are reviewing. I am particularly intersted if readers' writing styles share similar traits to the writing styles of the genre they read and review. I am currently still working on data processing and trying to deal with extremely large file sizes, so please let me know if you have any suggestions to make that process more efficient. Thank you!

## Notes

### Wilson

- **One thing I like:** You were very thorough with your data processing to make sure you had the data the way you wanted it, which was cool to see.

- **One potential avenue for improvement:** One idea for handling those especially large JSON files would be to split some of your code out into its own .py file, which would process the data and output it in a format that the notebook can more easily read (like a pickle.) It might also save a lot of code if you put your processing into a reusable function that could be called on any genre, so you don't have to re-write the same code over and over for every different genre.

- **One thing I learned:** It was funny that there were so many book format values in the dataset -- 209! -- including "three books in boxed set" and "Board Book Periodical". I would have assumed they had a standard set of formats, but maybe there's some way to add a custom format when adding a book?

**Ashley's Response:** Hi Wilson, thanks for your feedback! While I had some trouble using a .py file to process the data, I took your advice of pickling the data once it was processed rather than my strategy at the time of saving the data as a CSV. It made compiling my final dataframe much easier, so thanks for the suggestion!

## Seth

- **I Like**: The amount of work you put into cleaning up and rearranging your dataframes was incredible! The work you put in here will make the second phase of your project that much easier.

- **An avenue for improvement**: As Wilson said above, there is a lot of code that could potentially be simplified by allowing all repeat parts to be completed by a function. Also, for comparisons such as en-BR, en-US, eng, you could potentially simplify it to one comparison by comparing the first two characters to 'en' (if there are no other en languages).

- **One thing I learned:** I didn't realize review data would be as plentiful and useful as it is! A lot of your samples are filled with great data for analysis.

**Ashley's Reponse:** Hi Seth, thanks for your feedback! I definitely agree with you and want to find a way to better incorporate functions in the future of my project. I'll keep that in mind for my data analysis section especially if I will be doing repeat calculations on each genre so I can simplify my code. Thank you for the advice!

## Alex

- **One thing I like**: Your project plan is very thorough in establishing what your project is, and your annotation throughout your Jupyter Notebook makes it very easy to follow your process as you carve your data set into what you need. Overall very accessible and thoughtful.

- **One avenue for improvement**: I think that it's potentially fine for all the code to be written out if you're trying to be thorough in reading through the process. But maybe a note or something that let's readers know that you're going to start cycling through all the genres would be helpful as I wasn't entirely sure if you were done with your initial processing of the Children's data.

- **One thing I learned**: I haven't interacted with Goodreads a lot before, but I was really surprised at just how many languages are incoded into it's metadata!

**Ashley's Response:** Hi Alex, thanks for your feedback! You make a great point about explaining my process a bit more - I got so caught up in the data processing that I tended to forget those reading don't know what's going on unless I explain. I'll definitely go back and add some additional notes to make things more clear, especially when repeating the process through new genres. Thanks again!

## Soobin

- **One thing I like**:
    I like that you utilized `pickle` package a lot since handling this ginormous data could easily lead to crash.

- **One avenue for improvement**:
    The only thing to quibble is that, there could be a way to simplify the code in 51st cell. you are using '|' operator to filter the language code, and you can do the same operation if you use `.isin()` method.

- **One thing I learned**:
    I didn't know that we can use piping (|) in the python code!

**Ashley's Response:** Hi Soobin, thanks for your feedback! Believe me, I did cause my computer to crash many times! It was thanks to someone else's suggestion that I started pickling the files, so I really appreciate all your suggestions.

## Varun

- **One thing I like**:
    I like the data collection and preprocessing, you're doing a lot in a concise way!

- **One avenue for improvement**:
    Super small avenue for improvement, but in the data samples, I'm a bit confused what the indexes mean - it might mean something that I'm missing, but I would consider a quick .reindex() if not.

- **One thing I learned**:
    I learned how to use groupby in a quick, practical way. I've always had trouble with that.

**Ashley's Response:** Hi Varun, thanks for your feedback! You're completely right about the indexes - they're a bit messed up because of the sampling and joining, and I totally forgot to reindex. I'll go back and see if I can fix that, thanks for the suggestion!

## Sen

-**One thing I like**: How much work you've put into your project so far really shows. You approach the data from so many angles, including a bunch of descriptive stats, visualizations, paying attention to features such as numerical text features, sentiment, and POS. So thorough.

-**One avenue for improvement**: Commenting your code a bit more, especially for the larger code chunks, might be helpful to orient your reader (and future you).

-**One thing I learned**: I learned about NLTK's sentiment library. Looks like it'd be fun to experiment with.

**Ashley's Response:** Hi Sen, thanks for your feedback! I definitely agree about commenting and plan to go back and add a bit more step-by-step guidelines of my process. Thanks for pointing that out!

## Mack
1. It's really smart to include so many different linguistic elements of the reviews in your analysis. Looking at the data from several angles should help your results!

2. You have an entire notebook for analysis but have a small analysis section at the end of the compiling data notebook. Maybe move all the analysis bits together into one?

3. I learned about the nostril nonsense package! This is a really cool tool.
