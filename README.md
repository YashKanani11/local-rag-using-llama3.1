# local-rag-using-llama3.1
Hello everyone,
I just finished my little passion project on NLP. A fully local and free RAG application powered by the latest Llama 3.1:8b for embeddings and LLM. It takes user queries and gives the answer from the context of the specific document uploaded by the user. This makes the LLM aware only about the desired knowledge base and is highly unlikely to hallucinate.

Furthermore, I've also implemented 2 key features:
1. Whenever we add a new document to the training database, the app checks and re-embeds only the new documents.

2. The LLM also provides all the instances from which it concluded the given answer so the user can re-verify the answer.

And yeah, all local, no worries of data getting lost or being stolen or accessed by somebody else, excluding siblings with access to your computer.
