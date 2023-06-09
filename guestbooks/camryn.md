# Camryn's Guestbook

Thank you for visiting my guestbook. Any and all feedback is appreciated and helpful! :-) 

## Project Info

My project is titled [For Reddit Grammaticality Analysis](https://github.com/Data-Science-for-Linguists-2023/For-Reddit-Grammaticality-Analysis)

## Entries

## Seth
- **What I liked:** I found your choice of subreddits incredibly interesting! I had no idea 'lawyertalk' existed, and I imagine these will be fruitful in analyzing language data. I'm interested to see how internet lingo will weigh into grammaticality ratings.

- **An avenue for improvement:** Related to what I liked, it would be great to see more samples of the text you'll be analyzing! Much of it was only visible in previews when the head of a df was displayed. Also, although this isn't really an improvement, maybe pickling your dataframes instead of converting them to csv's will be easier to deal with in the future. This is just based on preference, though

- **What I learned:** I'm also working with Reddit/PRAW, so our tables are nearly identical in structure.Dropping nulls is a wise idea, and I may use your code as reference for handling my own tables!

### Camryn's response

Hi, Seth! Thank you for your feedback! I definitely should show more samples of the text I'll be analyzing, which I tried to do a bit of in my [Data Analysis Notebook](https://github.com/Data-Science-for-Linguists-2023/For-Reddit-Grammaticality-Analysis/blob/main/notebooks/dataAnalysis1.ipynb). I will definitely keep this in mind for any new progress I made and try to go back to older notebooks and add more samples! 

## Ashley 

- **Well Done:** Like Seth said, I think the specific subreddits you chose are awesome! The fact that you adapted your plan to go from looking at different geographical subreddits to different content subreddits shows that you have a strong linguistic focus in mind, and I think that change will be really beneficial. Your subreddits cover a wide range of different topics that I'm sure will show some linguistic differences - I particularly love ELIF and bet you'll find plenty of interesting things to explore!  

- **Suggestion:** I am not very familiar with reddit, but if I understand your data correctly it looks like the text is from the same person that wrote the title/made the post. Since some of your reddits seem to be more like forums for posing questions, is there a way to also collect data on different users' responses on the reddit thread? For example, subreddits like ELIF or Legal Advice seem like the most distinct language differences would be from the people responding to the posed question, talking simply like to a 5-year old or more sophisticated like a lawyer. I know you already have a lot of great data, but this could be something to explore!

- **What I Learned:** I learned a lot about what data scraping can look like when a website has an API designed specifically for it (I was going to use Goodreads' API for my project, but they discontinued it :( so I haven't been able to explore as much as I'd hoped). Your project gave me some great insight into what that process looks like and how to work efficiently with an API. 

### Camryn's response

Hi, Ashley! Thank you for your feedback. There is definitely a way to get comments and information regarding comments from a particular post. I wasn't planning on focusing on comments, but you bring up a really great point in terms of the people posting and responding to a post on a subreddit. I will see if I can find a way to bring that up in the next part of my analysis! 

## Alex

- **One thing I like**: I also agree that the collection of subreddits you implemented were very interesting, and that they do show a span in interests in subcultures that might meaningfully show differences in writing style. I do wonder if some of these subreddits will have higher likelihoods of people writing with English as an additional language (whether it's because it's a bigger subreddit or about a topic more or less niche to a certain culture), and if that might influence your results.

- **One avenue for improvement**: As your analysis centers around the grammaticality of the posts themselves, I was curious to learn how the additional information you save (like number of comments, upvotes, etc.) will play into your project in the future. They're definitely useful pieces of information to have, but maybe a comment somewhere explaining why they're maintained in your data set would be useful.

- **One thing I learned**: I'm also scraping info from Reddit for my project, and didn't really know how to initialize the API without sharing my private info, and I think the way that you do is is very straightforward and useful to keep in mind! 

### Camryn's response

Hi, Alex! Thank you for your feedback. I talk a bit about why I save certain information regarding posts, such as number of upvotes, in my [Project Plan](https://github.com/Data-Science-for-Linguists-2023/For-Reddit-Grammaticality-Analysis/blob/main/project_plan.md). Essentially, if time permits, I want to see if grammaticality has any impact on the interactions that a post my receive. I figured I would save that information to the dataframe while I was collecting them, instead of having to query for a bunch of additional information regarding 10k+ posts later, which is why they are there. But, you are definitely right in that I should have a comment explaining what information I collect and why in my notebooks.

## Wilson

- **One thing I like:** I think your repo is really well-organized -- I like how you outline its structure in the README and give an outline in the beginning of every notebook. (Unfortunately the outline links don't seem to work...)

- **One potential avenue for improvement:** Instead of printing out entire lists in the notebook, maybe just print a summary of the data or the head of the data. It makes it hard to navigate the notebook when there are hundreds of lines being printed from a single list.

- **One thing I learned:** I assumed `language-tool-python` would have issues with links, but it makes sense that it parses them (and other markdown syntax) correctly -- I actually have a VSCode extension that uses LanguageTool to spellcheck and grammar-check markdown and LaTeX files.

### Camryn's response

Hi, Wilson! Thank you for your feedback. I have fixed my issue of printing out large unnecessary lines of code, so my notebooks should be easier to navigate now, so thank you for pointing that out! Also, that is really interesting about the VSCode extension, I had no idea there was an extension that used that tool!

## Varun

- **One thing I like:** I like the analysis section in your notebook, it goes into detail and leverages knowledge of linguistic features that are relevant!

- **One potential avenue for improvement:** Similar to Wilson's comment, the printing makes the notebook get really long. Maybe have a quick summary instead.

- **One thing I learned:** I learned a quicker way to parse the praw output and quickly get features that are relevant to the post.

### Camryn's response

Hi, Varun! Thank you for your feedback. Like I said in my response to Wilson, I have since fixed the issue of printing out way too much. I wasn't aware this was an issue as Jupyter notebook collapses some of this output (as compared to GitHub where all of it is printed), so I definitely appreciate you both pointing that out for me! I am also glad my work helped you gain more information about parsing PRAW output.


## Soobin

- **One thing I like:** 
I like how simple yet efficient your codes are. Also, I learned another example of using `lambda x` function from your code. I also liked that you used different colors for different plots and it helped me understand that each plot is made out of different data set.

- **One potential avenue for improvement:** 
Only one thing I can thing of to quibble is, maybe reversing x axis and y axis in the plots could help a little. It was a bit hard to read what each bar stands for.

- **One thing I learned:** 
As I mentioned above, I learned many efficient coding skill from your code, including `lambda x` function. Seems like you almost finished it. Congrats! :D
 
### Camryn's response

Hi, Soobin! Thank you for your feedback. I also agree that the x axis labels are hard to read. I will try to find a better way of displaying that! I am also glad you learned something, specifically lambda x, from my code!

## Sen

- **One thing I like:** I like how you include a summary at the end of your notebooks to orient your reader and bring together your findings. Very clear and helpful. 

- **One potential avenue for improvement:** Your project looks like it's practically completed, so there's not a whole lot to say here, except some of the printed output in your notebooks is reaaally long, maybe there's a way to tidy that?

- **One thing I learned:** I learned about `language_tool_python`, which seems like it could have a lot of interesting uses for text/linguistic data, and saw a great example of how to use it. Thanks for the demonstration.