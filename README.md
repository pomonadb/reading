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

[1]: http://arxiv.org/pdf/1306.0493v1.pdf
[2]: https://www.cl.cam.ac.uk/~cm542/phds/johntang.pdf
