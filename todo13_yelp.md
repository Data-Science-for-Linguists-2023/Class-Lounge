# To-do 13: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 5-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Wilson:
- My laptop has 16GB of RAM (although WSL2 only has access to 8GB of it), a 6-core Intel i7-8750H, and a 1TB SSD (with 223GB free.) 100k lines were handled fine, taking only 6.4s to process, but 1 million was too much; it terminated (due to maxing out the RAM) after about a minute. The fact that every line was being read into a dataframe seemed like the culprit, so I tried re-implementing the same functionality using streaming (with ijson) and it actually halved execution time *and* was able to process the *entire* file in just under 4 minutes. Now I know that if I hit resource limits doing something like this, I can try refactoring my code so it processes the data line-by-line as a stream rather than loading it all into a dataframe.