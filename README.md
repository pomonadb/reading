# Reading

*Links and descriptions of topical articles and publications regarding temporal
networks and related works.*

1. [Graph Metrics for Temporal Networks][1] (Vincenzo Nicosia, John Tang, Cecilia Mascolo, Mirco Musolesi, Giovanni Russo, Vito Latora)
  - An overview of graph properties
  - Takes static graph properties and extends definitions to be applicable to
    temporal graphs

2. [Temporal Network Metrics and Their Application to Real World Networks][2] (John Kit Tang)
  - A PHD dissertation that provides an extensive explanation of analogies of
    metrics between static and temporal graphs (similar to paper [#1][1])
  - Contains info regarding analyzing real-world datasets (and their associated
    caveats and workarounds)
  - Contains references to many data-sets that can explored
  - Discusses complexities of various metrics (both theoretical and practical
    run times)
  - Temporal Graphs and Distance Metrics (Chapter 3)
    - Useful formal model for defining temporal graphs, temporal paths, etc.
    - Contains several high-level algorithms for finding these properties:
        - `TemporalShortestPaths()`
        - `TemporalShortestPathLength()`
  - Temporal Centrality Measures (Chapter 4) (RECOMMENDED READING)
    - Redefining centrality measures in temporal graphs
    - Applications and real-world implications of centrality measures: What can
      we actually predict with them? How can we use them to our advantage? How
      accurate are metrics?
    - Explains a variety of applications

3. [Finding Top-k Shortest Path Distance Changes in an Evolutionary Network][3],
    page 130 in print, 143 in pdf. (If link doesn't work, proceedings available
    through the library)
    - Talks about temporal changes in shortest paths
    - Introduces a set of estimation algorithms that provide an efficient way to
      measure these distances without needing to calculate the paths themselves.
    - The estimations calculated (Edge importance, Edge Rank metrics). Also
      contains static analysis of DBLP and IMDB using these metrics.  Though
      their interpretation of the data allows for infinite edge persistence.

4. [Path Problems in Temporal Graphs][4]
   (Huanhuan Wu, James Cheng, Silu Huang, Yiping Ke, Yi Lu, Yanyan Xu)
   - As the title implies, more discussions and algorithms pertaining to shortest
     paths
   - Includes theoretical and applied results

5. [DBLP — Some Lessons Learned][5] (Michael Ley)
  - Detailed explanation and background on the DBLP data-set in XML forms
  - Explains meaning of each entity; not as intuitive as the names
    of the entities (i.e. `www` can be treated as person)
  - Synonym and homonym problem with respect to people's names discussed

6. [Community detection in graphs][6] (Fortunato)
  - Describes state of the art for static community detection
  - Summary of community detection techniques

7. [Empirical Comparison of Algorithms for Network Community Detection][7]
    (Leskovec, Lang, Mahoney)
    - Compares many Static Community Detection Algorithms with results of
      example data sets. DBLP included

8. [Stability of graph communities across time scales][8]
    (Delvennea,Yalirakia,Barahonaa)
   - Markov Chain analysis of Random walks
   - Shows that the Markov Method gives a more general form of other methods,
    modularity and cut size.

9. [Discovering Temporal Communities from Social Network Documents][9]
   (Zhou, Councill, Zha, Giles)
    - Uses a tripartite graph (Authors, Words, and Venues) to analyze 
      community structure.
    - Analysis of DBLP.  Shows a good way to prune data and get a set
      of robust data.

10. [Defining and Evaluating Network Communities based on Ground-truth][10]
    (Yang, Leskovec)
    - Develop a gestalt notion of "true communities" based on knowledge of
      the specific data sets. 
    - Analyze algorithms for accuracy against this "truth."

11. [Analysis of Computer Science Communities Based on DBLP][11]
    (Biryukov, Dong)
    - Community analysis of DBLP with respect to the authors carreer and
      the field as a whole
    - Looks at different conferences and areas and how they grow and change
      w.r.t publication grpah rate, collaboration trends, and population
      stability.

12. [Time-Varying Graphs and Social Network Analysis: Temporal Indicators and Metrics][12]
    (Nicola Santoro, Walter Quattrociocchi, Paola Flocchini, Arnaud 
      Casteigts, Frederic Amblard)
    - Development of a formalism of Time-Varying Graphs, and analysize atemporal 
      vs temporal (quasi-)metrics over time.


[1]: http://arxiv.org/pdf/1306.0493v1.pdf
[2]: https://www.cl.cam.ac.uk/~cm542/phds/johntang.pdf
[3]: http://download.springer.com.ccl.idm.oclc.org/static/pdf/896/bok%253A978-3-642-22922-0.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Fbook%2F10.1007%2F978-3-642-22922-0&token2=exp=1456258394~acl=%2Fstatic%2Fpdf%2F896%2Fbok%25253A978-3-642-22922-0.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Fbook%252F10.1007%252F978-3-642-22922-0*~hmac=cdd5353eb909a9a89afb0c260db2fcdb80e7014e6026647e524c6d035164ba67
[4]: http://www.vldb.org/pvldb/vol7/p721-wu.pdf
[5]: http://dblp.uni-trier.de/xml/docu/dblpxml.pdf
[6]: http://snap.stanford.edu/class/cs224w-readings/fortunato10community.pdf
[7]: https://cs.stanford.edu/people/jure/pubs/communities-www10.pdf
[8]: http://www.pnas.org/content/107/29/12755.full.pdf
[9]: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4470321&tag=1
[10]: http://arxiv.org/pdf/1205.6233v3.pdf
[11]: http://arxiv.org/pdf/1012.5396v1.pdf


## Contributing New Links

To contribute new links, please make a PR so all participants are notified of
the additions. Please do not push directly to master.
