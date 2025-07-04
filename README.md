# embedding_PerAI



- Librerias:
pip install -q "qdrant-client[fastembed]>=1.14.2"



- Imagen Docker: 
docker pull qdrant/qdrant

- Contenedor
docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant

Se habilita puerto: http://127.0.0.1:6333/
Para visualizar la interfaz http://127.0.0.1:6333/dashboard

---
Recursos:
- [Embedding OpenAI](https://platform.openai.com/docs/guides/embeddings)