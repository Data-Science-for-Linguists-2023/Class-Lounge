# TITLE
Text-Based-Age-Recognition (https://github.com/Data-Science-for-Linguists-2023/Text-Based-Age-Recognition)

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
