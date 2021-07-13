### A dynamic graph embedding for COVID-19 graph

In this project website, we demonstrate our proposed dynamic graph embedding method, namely Dynamic Personalized PageRank Embedding (DynamicPPE) for learning a target subset of node representations over large-scale dynamic networks. We apply this method on a COVID-19 graph over the large English Wikipedia graph.

### COVID19-graph construction

Wikipedia graph construction: We collect the internal Wikipedia Links (WikiLinks) of English Wikipedia from the beginning of Wikipedia, January 11th, 2001, to December 31, 2020 where We collect the data from the [dump](https://dumps.wikimedia.org/enwiki/20210101/). During the entire period, we collection 6,151,779 valid articles. We generated the WikiLink graphs only containing edge insertion events.

Since the structural changes can be well-captured by graph embedding, we use our proposed method, [DynamicPPE](https://arxiv.org/abs/2106.01570) to investigate whether anomalies happened to the Chinese cities during the COVID-19 pandemic (from Jan. 2020 to Dec. 2020). For more details of algorithm implementation see [DynamicPPE](https://github.com/zjlxgxz/DynamicPPE).

### Contact

This project website contains the deliverable of Northeast Big Data Hub Seed Fund project (Award number:89931-1165360-1/AWD00002014). This project website is maintained by [Baojian Zhou](https://baojian.github.io/). Any questions can be sent to baojian.zhou at cs.stonybrook.edu.
