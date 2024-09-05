<h2 align= "center"><em>Search Engine Elastic Search</em></h2>

<div align="center">
  <img height="200" src="https://github.com/shreyjain99/Search-Engine-Elastic-Search/blob/main/src%20files/cover%20image.jpg"/>
</div>

<hr width="100%" size="2">

<body>
    <h1>Search Engine Project Overview</h1>
    <p>The project demonstrates a complete pipeline from data indexing to search functionality, leveraging ElasticSearch for efficient retrieval and the Universal Sentence Encoder for improved semantic understanding of queries and documents.</p>

  <h2>Indexing and Search Methods</h2>
    
  <h3>indexES.py</h3>
  <p>The <code>indexES.py</code> file creates an ElasticSearch index called <strong>"questions-index"</strong> and populates it with question titles and their vector representations.</p>

   <h3>searchES.py</h3>
  <p>The <code>searchES.py</code> file implements two search methods:</p>
    <ol>
        <li>
            <strong>Keyword Search:</strong> Uses ElasticSearch's match query, which leverages the inverted index for efficient text searching.
        </li>
        <li>
            <strong>Semantic Similarity Search:</strong> Uses vector representations and cosine similarity for more advanced, meaning-based searching.
        </li>
    </ol>

  <p>By combining the power of inverted indices for fast keyword matching and vector representations for semantic understanding, this implementation creates a robust search engine capable of handling both traditional text searches and more nuanced, meaning-based queries.</p>
</body>
