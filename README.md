# trial-test-case
## Solution Description
The main idea of the solution is to return the standard phrases most similar to the phrases from the text. The solution begins with text processing, then the text is vectorized and a matrix of similarity with standard phrases is created. The results of the matrix are sorted and the best results are returned.
The output is phrases that can be inserted into the text instead of similar phrases in the text
## Advantage
1. Simplicity
2. Speed (the solution is faster than CountVectorizer+CosineSimilitary)
3. Improvability, can add a Epsilon from which phrases will be replaced
4. This solution is easy to **transfer into production**, unlike more complex models
