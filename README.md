# Local-RAG

## Flow Chart

### Contents:
1. Open a PDF document (you could use almost any PDF here).</br>
2. Format the text of the PDF textbook ready for an embedding model (this process is known as text splitting/chunking).</br>
3. Embed all of the chunks of text in the textbook and turn them into numerical representation which we can store for later.</br>
4. Build a retrieval system that uses vector search to find relevant chunks of text based on a query. Create a prompt that incorporates the retrieved pieces of text.</br>
5. Generate an answer to a query based on passages from the textbook.</br>
6. The above steps can broken down into two major sections:</br>

#### Document preprocessing/embedding creation (steps 1-3).
1. Search and answer (steps 4-6).</br>
2. And that's the structure we'll follow.</br>

It's similar to the workflow outlined on the NVIDIA blog which details a local RAG pipeline: </br >https://developer.nvidia.com/blog/rag-101-demystifying-retrieval-augmented-generation-pipelines/

![image](https://github.com/srsapireddy/Local-RAG/assets/32967087/b391d0a2-5bb7-410b-a14a-1c4508469454)

### References:
[1] Paper: https://arxiv.org/pdf/2005.11401.pdf
