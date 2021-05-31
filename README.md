# Search-Engine-based-on-text
It is an Implementation of a text-based version of a Search Engine *(Similar to that of Google, Bing, Baidu etc.,)*

Most search engines are built on top of an inverted index (or) index for short, an index is a structure, where for each term, we have a list of documents that this term appears in.
So, we'll build index based on the set of files.

## Functions used in the our program *(searchengine.py)* 
 1. We create a index using "create_index" function. Which stores the words and the list of files in which a word appears in.
 2. The same "create_index" function has a parameter which stores the file names and there titles
 3. The common files are identified using a function "common". This function takes in two lists as arguments, compares them and returns a list with the common files.
 4. The `search` function which takes our query and searches for the files in which we can find our query with the help of a function "common".
 
## Testing our program
  1. To check the working of the program we are using "test1.txt" and "text2.txt" files
  2. We later check our program with the files in "small.zip".
  3. We finally test our program with the files in "bbcnews.zip".
