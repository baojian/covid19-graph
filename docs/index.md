### Project Description

In this project website, we demonstrate our proposed dynamic graph embedding method, namely Dynamic Personalized PageRank Embedding (DynamicPPE) for learning a target subset of node representations over large-scale dynamic networks. We apply this method on a COVID-19 graph over the large English Wikipedia graph.

### COVID19-graph construction

Wikipedia graph construction: We collect the internal Wikipedia Links (WikiLinks) of English Wikipedia from the beginning of Wikipedia, January 11th, 2001, to December 31, 2020 where We collect the data from the [dump](https://dumps.wikimedia.org/enwiki/20210101/). During the entire period, we collection 6,151,779 valid articles. We generated the WikiLink graphs only containing edge insertion events.

Since the structural changes can be well-captured by graph embedding, we use our proposed method, [DynamicPPE](https://arxiv.org/abs/2106.01570) to investigate whether anomalies happened to the Chinese cities during the COVID-19 pandemic (from Jan. 2020 to Dec. 2020). For more details of algorithm implementation see [DynamicPPE](https://github.com/zjlxgxz/DynamicPPE).

### Embedding Evolution for COVID-19

We target nine Chinese major cities and keep track of the embeddings in a 10-day time window.  From our prior knowledge, we expect that Wuhan should greatly change since it is the first reported place of the COVID-19 outbreak in early Jan. 2020. More details can be found in Section 5 of our paper, [Subset Node Representation Learning over Large Dynamic Graphs](https://arxiv.org/abs/2106.01570).

### Contact

This website is maintained by [Baojian Zhou](https://baojian.github.io/). Any questions can be sent to baojian.zhou at cs.stonybrook.edu. This project is supported by [Northeast Big Data Hub Seed Fund](https://nebigdatahub.org/seedfund/)(Award number:89931-1165360-1/AWD00002014).

### Reference
[1] [Xingzhi Guo, Baojian Zhou, Steven Skiena, Subset Node Representation
Learning over Large Dynamic Graphs, KDD, 2021](https://arxiv.org/abs/2106.01570)
