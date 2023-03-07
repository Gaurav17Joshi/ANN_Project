# ANN_Project

Broad Plan to make the LSH enabled query search:- 
1) Make a data_folder directory and keep all the data in it
2) In data_loader.py load the data, clean it, the put all the sentences with their index in a separate file.
3) Process the data to its vectors and store the vectors(signatures) in the same csv, keep the 20 hashing vectors and the dictionary in the imp file as lists.
4) Make a lsh class that processes the data and then outputs a dictionary for all the candidate pairs, with their sub vectors, store it in the imp file as a dictionary
5) Create a query python file, which takes a sentence as a query and processes from the dictionary to print the matching sentences

Report Plan:-
1) 1 page for explaining Hashing, motives, methods
What is hashing, methods of hashing, Properties of good hash functions.
2) 1 page for explaining LSH, various methods
What is an LSH and how is it different form hashing, mathematical basis, different Lsh and their functions, and and or of lsh functions
3) 1 page for vector embeddings
What is a vector embbedding and how are they useful in ANN, it mathematical defination, different types of embeddings and their how they are made.
4) Explaining how we are using these three concepts and how we are implementing our query search
Our method in detail, photos of generated results and timing plots for sentences, sentence length vs plot, also make plots of candidate features vs their jaccard, angular distance.
5) How we could have improved our model
Think over it
6) LSH query search's theoretical time complexities
From wikipedia
7) Use of LSH in various fields especially ML, and big companies
From Hugging Face and reesearch papers

//////   Make Subsections    \\\\\\
