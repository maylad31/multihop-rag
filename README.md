How minor adjustments in query preprocessing and prompt refinement could enhance retrieval and final outcomes: MultiHop-RAG is a QA dataset to evaluate retrieval and reasoning across documents with metadata in the #RAG pipelines. It contains queries, with evidence for each query distributed across 2 to 4 documents. I first tried a simple retrieval. For inference_query type the results were not that bad. But for other query types(comparison and temporal), the results were quite poor. Then, I tried to see if we can improve for other query types by minor query preprocessing(trying to get more relevant chunks by breaking the query into relevant phrases) and by tweaking the prompt a bit.

I observed a notable improvement. While some responses were incorrect, the overall improvement from the previous version was significant. We can try to tweak the prompt, use a better model(gpt4), experimenting with different strategies (make better use of metadata, try different chunking methods), may be create a knowledge graph. My aim was not to get the best accuracy but to see whether minor adjustments in query preprocessing and prompt refinement could enhance retrieval and final outcomes. And it does.


Connect with me on linkedin if you have an intersting project/common interests. 
https://www.linkedin.com/in/mayankladdha31/
