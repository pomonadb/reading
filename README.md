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

[1]: http://arxiv.org/pdf/1306.0493v1.pdf
[2]: https://www.cl.cam.ac.uk/~cm542/phds/johntang.pdf
[3]: http://download.springer.com.ccl.idm.oclc.org/static/pdf/896/bok%253A978-3-642-22922-0.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Fbook%2F10.1007%2F978-3-642-22922-0&token2=exp=1456258394~acl=%2Fstatic%2Fpdf%2F896%2Fbok%25253A978-3-642-22922-0.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Fbook%252F10.1007%252F978-3-642-22922-0*~hmac=cdd5353eb909a9a89afb0c260db2fcdb80e7014e6026647e524c6d035164ba67
