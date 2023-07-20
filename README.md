# Camembert-Embedder

Implementation of the embedder sentence-camambert-base.
The large is not working rn on my machine.

Parsing some PDFs into chunks (1 chunk = 1/2 PDF page).
Then embed those chunks and one query (representing one question on these documets) using *camembert-base*.
Then compute Cosine Similarity score for each query-chunk pair and display the TOP-5 best scores.
