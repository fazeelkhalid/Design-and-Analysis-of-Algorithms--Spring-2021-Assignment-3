# Design and Analysis of Algorithms  Spring 2021 Assignment 3
 Problem 1 Suppose you want to place bill boards to advertise about your new business on the roads of your city. The idea is to place billboards only on the junctions to get maximum visibility as lots of people pass through those junctions. Placing a bill board cost you X Rs. You want to place these bill boards such that each road of the city is covered (i.e. one board must be placed at least to one of the junctions connecting that road). Your objective is to place the boards such that all roads are covered with minimum cost. Being a computer science expert, you model the road network as a graph where roads are edges and junctions are vertices. One of your friends asks you to apply greedy approach to minimize your cost. He asks you to place a board on the junction/vertex that has maximum degree (this way maximum number of roads will be covered) and then place the next board on the junction/vertex that has maximum uncovered roads. Keep doing this until all roads are covered. Is this greedy strategy optimal? If yes then give an informal correctness proof. Otherwise give a counter example. 
 Problem 2 You are recently appointed as an intern of company ABC for n weeks. You team lead has assigned you n tasks t1, t2, t3, ... , tn. You have to submit one task every week but you can do these tasks in any order. Each task i requires hi hours to complete (h1 hours for task t1, h2 hours for task t2 and so on). If you submit task ti on week j then you will be paid hi*(n-j)$. You want to maximize your earning. Give a greedy algorithm that can determine the order in which you should perform the tasks to maximize your income. Give n informal proof of correctness for you algorithm.
 Problem 3 We use Huffman's algorithm to obtain an encoding of alphabet {a, b, c} with frequencies fa, fb, fc. In each of the following cases, either give an example of frequencies (fa; fb; fc) that would yield the specified code, or explain why the code cannot possibly be obtained (no matter what the frequencies are). (a) Code: {0, 10, 11} (b) Code: {0, 1, 00} (c) Code: {10, 01, 00} 
 Problem 4 Ternary Huffman. Trimedia Disks Inc. has developed ternary hard disks. Each cell on a disk can now store values 0, 1, or 2 (instead of just 0 or 1). To take advantage of this new technology, we need a modified Huffman algorithm for compressing sequences of characters from an alphabet of size n, where the characters occur with known frequencies f1, f2, ..., fn. Your algorithm should encode each character with a variable-length code word over the values 0, 1, 2 such that no code word is a prefix of another code word and so as to obtain the maximum possible compression. a. Design an algorithm for finding optimal code. b. Analyze the running time of your algorithm as a function of n, the number of unique characters. c. Prove that your algorithm works (Give informal argument).
