# Information-Retrieval

Building Weighted TF-IDF Model, Introducing Spell Error Correction and Improving Efficiency of Model.

Task 1 Weighted TF-IDF Model
(a) Implement a weighted TF-IDF model M f ull for I f ull . Rank the documents as per their relevance score. Display the top 20 results (decreasing order of score) in form of a table. Format:
Query ID  Doc IDs       Scores
123       1, 2, 5, 6    0.7, 0.66, 0.56, 0.4
(b) Improve the top-K precision of your model. Plot a grouped bar plot for top-K precision and recall of M P . X axis has query ID, Y axis has scores and legends represent the Precision and Recall. Plot three subplots for K = 2, 5, and 10. If number of results are lesser than 10 then plot the result for maximum value
available.

Task 2 Spell Error Correction
(a) Induce minimum three spell errors randomly in your query words: i) W1: delete one character, ii) W2: insert and delete one character, and iii) W3: swap two random non-adjacent characters. Display the potential correct term based on the Levenshtein edit distance score for each query. You can define a threshold
for selecting the term. Cost of insertion = deletion = 1, substitution = 2. It should not be too less or too large. Result format:
Query ID  Typo                      Term Distance
123       Infotmarion Information   4
(b) Using the same threshold as Task 2a, improve the top K precision for your queries. K = 5 and 10. Refer this model to as M spell . Display results in a suitable format.
(c) Using the same set of queries from Task 2a, Display the potential correct term based on the QWERTY edit distance score for each query. Assume that the first character of every word in query is correct.
(d) Using the same threshold as Task 2a, and updated queries after addressing QWERTY typographical errors, improve the top K precision for your queries. K = 5 and 10. Refer this model to as M qwerty .

Task 3 Efficiency Model
(a) Display the time (in seconds) taken by M f ull , M P , M spell , and M qwerty for each respective query.
(b) Implement a heuristic to improve the efficiency of your models M f ull , M P , M spell , and M qwerty , i.e., reduce the time taken by each model. 
