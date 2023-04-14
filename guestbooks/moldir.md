## Guestbook

Hi! This is Moldir's guestbook. Thanks for visiting and I look forward to your feedback.

## Project

I am working on a project titled 'Kazakh-Russian code-switching analysis,' which you can find [here](https://github.com/Data-Science-for-Linguists-2023/Kazakh-Russian-Code-Switching-Analysis). I am currently facing some difficulties with annotating the conversational data in text files, and I would really appreciate any suggestions you may have for easy-to-use annotation tools. Thank you for your help in advance!

## Notes  

### Mack
I really like your topic! It seems very interesting and I am excited to see how it goes.

1. I thought the overall structure of your repo was very easy to follow and understand the goals of your project and what progress you have made thus far. Very good narrative to help me follow along with your code and your annotation plan.

2. This may be cumbersome to do for the entire project but maybe just for some examples provide English translations. I know it isn't the main focus of your project but it will help the English-speaking audience better understand your research.

3. I learned that Kazakh speakers code switch to Russian *within* words! I am familiar with inter- and intra-sentential switching but this is the first I've heard of intra-word code switch.


### Moldir's response

Thank You, Mack for your feedback! I appreciate it. Yes, I am working on translating examples of code-switching types for my presentation and analysis. As you noticed, it wouldn't be possible to translate all of instances code-switching but I will make sure that each CS type has a proper example and explanation on my final report.


### Camryn

I think you have a lot of great work done so far! One thing I really liked is that your jupyter notebook for the datasets was really well formatted, which made it really easy to read and understand what is going on. For example, I really like that you included advantages/disadvantages, and included a spot in the notebook about your future work. 

One thing that I think you could improve on is organizing your repository. Having folders or having explanations of what something is and where it is would be super helpful instead of having it all in main part. I also agree with the feedback above that including someEnglish translations would be helpful!

I learned that Kazakh-Russian code switching is very common because most Kazakhs are bilingual! 


### Moldir's response

Hi Camryn, thanks so much for your feedback! I reorganized my repo based on your suggestions and hope it looks more readable now:-)


### Ashley

1. This is a very impressive project! I particularly liked the summary you included at the bottom of your "Annotated Dataset" JNB as some of the code was a bit more advanced than I am used to deciphering, but that summary helped me better understand the key takeaways from your data exploration. Your process was incredibly thorough and you did a great job exploring a smaller data sample to really get a feel for the strucutre and content of your data before applying your methods to the full dataset.

2. I know you aren't able to share most of your data, but one suggestion I would give is (if possible) to include an example of an utterance with your codes attached. We can see your annotation scheme as well as the counts of different annotations in your JNB, so having an example to see how those codes are being interpreted and applied to an actual piece of text could help put those pieces together and further clarify your annotation process. 

3. Like Mack said, I learned that code switching can occur intra-word, which is something I hadn't heard of previously. It was especially interesting to learn that intra-word code switching can occur by attaching an affix of one language to a stem of another language, which is fascinating.  


### Moldir's response

Thank You for the feedback, Ashley! Since I am working with a standoff annotation (offline) format (meaning annotations are stored separately from the annotated text) shared annotated samples contain only categorical and numerical values like the code-switching tags and subtags and their positions in the text. The API key can be used to map annotations to the text. For security purposes, I am using the API key locally only (as of now). 


## Alex

- **One thing I like:** The data set you're using seems incredibly thorough and complex, and so I really appreciate how thoroughly you explore the data set prior to doing your analysis. And, because your data set is so complex, I appreciated how you would explain and summarize the work you're doing to the reader, for example when you stop and explain what the "recusive_parser" function is.

- **One potential avenue for improvement:** In annotatedDataset.ipynb, after \[62],you comment that "Cyrillic characters are not recognized!" Because I'm unfamiliar with the data set I'm not sure how the work you did prior to that shows that conclusion, so maybe an explanation of what's happening there could be useful. I think it has something to do with Labelbox? But overall it seems really important to your project that Cyrillic character's aren't recognized there! 

- **One thing I learned:** I found out about the Labelbox platform, which seems like a really valuable tool in annotating data!


### Moldir's response

Hi Alex, thank you for your feedback! Initially, the Cyrillic characters were not recognized in the annotated text samples. However, I was able to resolve this issue by using decode("utf-8") method on the annotated text. My apologies for not updating the notes accordingly.

 
## Varun

- **One thing I like:** Looks like a lot of raw data processing and parsing, good job! I also really like the end of your JNB which has the summary and future work.

- **One potential avenue for improvement:** Maybe some more detail about the workflow described [here](https://github.com/Data-Science-for-Linguists-2023/Kazakh-Russian-Code-Switching-Analysis/blob/main/screenshots/annotation-workflow.png). It looks super cool, I want to know more!

- **One thing I learned:** Basically everything about this topic is new to me, I'm very impressed.


### Moldir's response

Thank you for the feedback, Varun! The workflow description can be found [here](https://github.com/Data-Science-for-Linguists-2023/Kazakh-Russian-Code-Switching-Analysis/blob/main/progress_report.md) under the progress report md file.

### Wilson

- **One thing I like:** I really like the organization of your work -- it makes it easy to understand what's going on and what observations you're making.

- **One potential avenue for improvement:** It's a little hard to tell what the JSON data actually represents -- maybe some kind of visualization would help? That might be nice for the presentation especially.

- **One thing I learned:** The whole annotation workflow (and this method of annotating) is totally new to me -- it was really interesting to read about.


### Soobin

- I liked how you explained the intra- inter- sentential examples, reader-friendly. This is very interesting topic and I think it could be extended to other common type of bilingual pair such as spanish-english. Also, I can see your hard working on annotation. Very impressive!

- I can understand visualization in your project is a little hard, but maybe you can make more visualizations such as the count of inter- intra- sentential code switching. 

- I learned about the `labelbox` platform, which I might need in the future. Great job Moldir! :D