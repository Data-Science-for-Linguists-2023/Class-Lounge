# Ashley's Guestbook

Thanks for checking out my guestbook! Any feedback is greatly appreciated.

##  [What's the Story?: Linguistic Variation in Goodreads Reviews by Genre](https://github.com/Data-Science-for-Linguists-2023/Goodreads-Genre-Reviews-Analysis)

For my project, I am curious to see if the written language style used by readers differs depending on the genre of book they are reviewing. I am particularly intersted if readers' writing styles share similar traits to the writing styles of the genre they read and review. I am currently still working on data processing and trying to deal with extremely large file sizes, so please let me know if you have any suggestions to make that process more efficient. Thank you!

## Notes

### Wilson

- **One thing I like:** You were very thorough with your data processing to make sure you had the data the way you wanted it, which was cool to see.

- **One potential avenue for improvement:** One idea for handling those especially large JSON files would be to split some of your code out into its own .py file, which would process the data and output it in a format that the notebook can more easily read (like a pickle.) It might also save a lot of code if you put your processing into a reusable function that could be called on any genre, so you don't have to re-write the same code over and over for every different genre.

- **One thing I learned:** It was funny that there were so many book format values in the dataset -- 209! -- including "three books in boxed set" and "Board Book Periodical". I would have assumed they had a standard set of formats, but maybe there's some way to add a custom format when adding a book?

## Seth

- **I Like**: The amount of work you put into cleaning up and rearranging your dataframes was incredible! The work you put in here will make the second phase of your project that much easier. 

- **An avenue for improvement**: As Wilson said above, there is a lot of code that could potentially be simplified by allowing all repeat parts to be completed by a function. Also, for comparisons such as en-BR, en-US, eng, you could potentially simplify it to one comparison by comparing the first two characters to 'en' (if there are no other en languages).

- **One thing I learned:** I didn't realize review data would be as plentiful and useful as it is! A lot of your samples are filled with great data for analysis.
