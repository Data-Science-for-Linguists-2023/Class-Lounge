# TITLE

This is Soobin's Guestbook

# Project

I am working on TED talk transcript and its rating. I am trying to build a classifier that can predict the rating of the talk based on the transcript. I am planning to use the vocab level as a independent variable for my project, and my current hypothesis is that the lower the vocab level is in the transcript, the higher (or the more positive) the rating would be. Why? IDK, I am just a person who does not like jargons so I thought other people would be the same? lol. If any other hypothesis you think, please let me know down below.

[Soobin's Term Project][https://github.com/Data-Science-for-Linguists-2023/TED-Talk-Rating-Analysis]

# Notes

## Sen's Notes
Soobin, I think that you've chosen an interesting topic, and I'm curious to see what you find out. From checking out your code, I learned some new functions and methods.

Based on your summary and progress report it seems you are still trying to figure out a working hypothesis. I think there are a lot of different lexical or linguistic features of speeches/talks that could affect the popularity or engagement that it receives. Some that come to mind are the speaker's tone, interrogatives like rhetorical questions, personal language, and emotional langauge, so you could try investigating those. You could also take measurements of features such as TTR and average sentence length to see if viewers prefer talks with more simple straightforward language or more complexity.

-- Hey Sen! Thanks for your feedback. I've never told you, but I want to say that I always appreciate your help and support. You mentioned sentence length, and I am considering to use sentence length as an indicator of negative review because there is one ratings called 'long-winded', and Dr. Han suggested me to consider the correlation between them. Thanks a lot again and see u soon in class *kiss kiss*

## Mack's Notes

I like the various hypotheses you have about what you think you will find. A lot of them make sense and I am curious if your analysis will support the hypotheses or generate something unexpected.

1. It seems like you've spent a lot of time working with the data and you've look at it from several different angles. I think bringing in Kband data was a great idea.

2. I think your notebook could use a little more commentary to help the reader understand what you are doing at each step and why. You've done a lot of great work wrangling with the data, so some comments and text will help us follow along.

3. I did not know there were these data out there on TED talks.

-- Henlo Mack! Thanks for your feedback. Like I said above to Sen, I always appreciate your support in so many aspects of my life. Soooo, it seems like my data is giving me something that I didn't expected in the beginning of this journey. Hope that I can get something interesting to you! :) see ya *muah*


## Seth's Notes

Hi Soobin!

1. One thing you did well

There are a lot of things to pick from, but one particular thing that impressed me was your data exploration. Your notebook was really easy to follow in this regard, and things like the .dropna not dropping nulls was well-explored!

2. One avenue for improvement

You did everything thoroughly! One nitpick I have is that, toward the end of the notebook, the notes are in Korean. Having an English translation for each Korean sentence would be great, as I found myself throwing words into google translate

3. One thing I learned

The method you used to calculate positive vs. negative reviews for each TED talk was clever!

-- Hi Seth! Thanks a lot for your comments. And sorry for bothering you with my Korean comments. I left it in Korean thinking that I will revise it later, and I forget.

## Camryn's Notes

1. You have a great level of exploration and analysis within your notebook. I think your findings are really fascinating. In addition, I really like your comments throughout your notebook, they make it easy to follow what is going on.

2. I think what you have is great, but it could be beneficial to add some more comments and summary towards the end of your notebook regarding results and what they mean. I also think you should add some more graphs to your notebook for visualizations!

3.  Your way of calculating and classifying reviews was very advanced and I definitely learned something from your work with the all of the numbers in your analysis.

-- Hi Camryn! Thanks for your suggestion. I forgot about adding visualization, which is an important part of this project! I will add plots for the better understanding of the result :)
    follow-up comments: Hey Camryn! So, I tried more visualization in the analysis part after reading your feedback, and I found something totally unexpected and so interesting. I owe this to you (& Ashley) haha. Thanks!

## Moldir's Notes

1. I like your topic and how you are stating/exploring multiple hypotheses! Very impressive! Look forward to see what you will find out at your final report. Also, your repo looks tidy and well-organized! Easy to follow and look around.

2. One suggestion I can think of is to attach the links on the READ.ME file to the corresponding words. The markdown syntax for that would be: [the key word](the corresponding link). In this case, the key word will be highlighted only, and the link will be hidden which makes the text more accessible. 

3. I have learned that we can build a model to explore the correlation between the ratings and the text. 

-- Hello Moldir! Thank you for your comments. But I am not very sure what you mean by 'corresponding words'. I think I should ask you tomorrow after class ;) 

## Ashley's Notes

1. You did a great job wrangling with the with the Ratings data and finding a way to add that to your dataframe. I liked how you tested out your code on smaller samples before working on all the data, and I shared your excitement when you finally got it to work! 

2. One suggestion would be to include some more visualizations. I really liked the graph you included to show no correlation between k-band and comments, so especially once you get into developing your classifier, more visualizations like that would be helpful to understand the data better.

3. I was surprised to learn how many different variations of Ted Talks there were, especially that some (like with the high average k-bands), can be performances. Very interesting, and good job digging into your data!

-- Hi Ashley! Thanks for your feedback about my project. I tried to put more visualization in my analysis after reading your comments, and I found something totally unexpected! All credits to you & Camryn :D thanks a lot!!


# Alex's Notes

1. I really enjoyed reading through your process as you cleaned your data set and decided on what you defined as a positively or negatively rated talk. I think it shows a lot of thoughtful considerations for your goals for this project as you worked out what information was available and how you could use that information for your analysis.

2. One suggestion is to maybe include an example of what the most "obnoxious", most "longwinded", etc. talk is prior to your analysis of it so that we could get for ourselves of what might lead someone to rate a talk that way to justify the processes you're doing on them. I agreed with your hypothesis of "obnoxious" having a higher k-band, but it would be interesting to have a TED talk to point at and say "this one is jargony and the reviews think it's obnoxious."

3. I was really interested in seeing the NB model that started overfitting when you increased the number of features! I've never seen accuracy go down in that way on my own projects and so I think it's valuable to see the limits of different models in action.

-- Hello Alex! Thanks for your suggestion. I added the examples of talks for the presentation after reading your suggestion cause I thought it would be interesting to ask you guys' opinion on the examples, like would you guys rate it as obnoxious or longwinded after reading the example. (I couldn't do this because of the time limit thought.. lol) Anyway, thanks again for your opinion and good luck with your everything! 

## Wilson's notes

- **One thing I like:** Your progress reports are very descriptive and make it easy to tell what exactly you did in each step.

- **One potential avenue for improvement:** There are a few techniques to deal with imbalanced datasets you might want to use to help deal with the issues you're having with your models. The relatively small sample size is a bit limiting, though.

- **One thing I learned:** I didn't know TED talks had that kind of rating system - I can imagine a lot of interesting analysis that could be done with that!

-- Hi Wilson. Thanks for your suggestion. I also asked for an advice to Dr. Han regarding the imbalance in the datasets, but she told me not to worry much. (I still don't get the meaning of it though. lol) Anyways, thanks a lot for your comment and good luck with your everything! :)
