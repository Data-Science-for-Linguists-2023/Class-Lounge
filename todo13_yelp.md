# To-do 13: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 5-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Wilson:
- My laptop has 16GB of RAM (although WSL2 only has access to 8GB of it), a 6-core Intel i7-8750H, and a 1TB SSD (with 223GB free.) 100k lines were handled fine, taking only 6.4s to process, but 1 million was too much; it terminated (due to maxing out the RAM) after about a minute. The fact that every line was being read into a dataframe seemed like the culprit, so I tried re-implementing the same functionality using streaming (with ijson) and it actually halved execution time *and* was able to process the *entire* file in just under 4 minutes. Now I know that if I hit resource limits doing something like this, I can try refactoring my code so it processes the data line-by-line as a stream rather than loading it all into a dataframe.

## Varun:
- I tried it on my Macbook Pro, 8 gigs of ram. It did not take it well when I attempted to read it all in at once. My computer fan started being extra noisy, my terminal went unresponsive and so did the rest of the computer, even to keyboard interrups. I managed to kill it with the classic `CTRL+\`, but had to restart my computer because nothing worked. Upon restarting, my wallpaper was changed for some reason. A part of the problem might be because of the 100 chrome tabs I that will never close (I need all of them). I tried again, specifying `chunksize`, and it took a few minutes but worked.
