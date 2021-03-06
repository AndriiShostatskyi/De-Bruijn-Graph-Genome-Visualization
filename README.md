# De-Bruijn-Graph-Genome-Visualization
Builds de Bruijn graph from genome reads and visualizes in browser using vis.js. It's meant to be used for relatively small data sets and helps when learning genome sequencing algorithms.

In order to use it, simply open index.html, select kmer size, width and height of network canvas, and provide reads of genome; then click on 'Display'. Kmers are displayed as edges between nodes.

#### Example of visualization # 1
Kmer size is 3. Input:
```python
AACG
AAGG
ACGT
AGGT
CGTT
GCAA
GGTT
GTTG
TGCA
TTGC
```
We can observe the graph is cyclic and has one bubble.
![Example](https://github.com/AndriiShostatskyi/De-Bruijn-Graph-Genome-Visualization/blob/master/imgExps/GraphExample_1.png)

#### Example of visualization # 2
Kmer size is 7. Input:
```python
AAAAAAAAAAAAAATATTTTTATTAAATAATTAAAATAAGAAAAAATAAAAA
```
We can observe the graph has bubbles and a tip.
![](https://github.com/AndriiShostatskyi/De-Bruijn-Graph-Genome-Visualization/blob/master/imgExps/GraphExample_2.png)

### Example of visualization # 3
We can observe the graph is quite dense, has bubbles and tips.
![](https://github.com/AndriiShostatskyi/De-Bruijn-Graph-Genome-Visualization/blob/master/imgExps/GraphExample_3.png)
