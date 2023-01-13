# Parallel-Computing-MapReduce
In this assignment, I wrote a parallel map reduce program with the use of PyMP given a set of words
among a set of documents that constitute the words of Shakespeare. The set of words is listed below.
The assignment used a map-reduce design pattern to split up the work where every process split of the
the work for every document and combined the individual words.

The program should output the total instances of all words and the counts for each individual word

Word list:
hate, love, death, night, sleep, time, henry, hamlet, you, my, blood, poison, macbeth, king, heart, honest

## Requirements 

The program shall count the number of each instances of each word for the set of documents, and the total of count of all words in the list

The program shall use PyMP to compute the number of words in parallel

The program shall time how long overall operation takes and how long the word count and file reading operations take individually
