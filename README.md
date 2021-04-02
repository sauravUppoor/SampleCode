This repository contains codes used for testing various examples for the proposal. The algorithm I proposed to implement is `Brandes' Betweenness Centrality` which is used to calculate centrality values of each node.

The algorithm has been tested on various types of graphs like:
1. Unweighted Undirected
2. Weighted undirected
3. Unweighted directed (pgRouting sample data)

### Requirements
 - GNU G++ / MSVC compiler
 - Boost C++ Library

### Compilation
```
c++ -I path/to/boost_1_75_0 example.cpp -o example 
```

### Run
```
./example
```

More details: https://boost.org/doc/libs/1_75_0/more/getting_started/unix-variants.html

### Visualisation
1. Weighted undirected graph

<p align="center">
  <img src="https://github.com/sauravUppoor/SampleCode/blob/main/img/ex1.gif" alt="gif1" width="350px">
</p>

2. Unweighted directed graph (pgRouting sample data)