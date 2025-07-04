# embedding_PerAI



Librerias:



pip install -q "qdrant-client[fastembed]>=1.14.2"



Docker: 
docker pull qdrant/qdrant

docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant



---
Recursos:
- [Embedding OpenAI](https://platform.openai.com/docs/guides/embeddings)