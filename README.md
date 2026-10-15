# Awesome-Vector-Similarity-Search

# Top Vector Similarity Search Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Vector Databases, ANN Indexes, Embedding Search, RAG Retrieval & Semantic Similarity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vector Similarity Search**. These systems store embeddings and retrieve nearest neighbors—powering RAG, recommendations, multimodal search, and semantic memory.

**Examples** include Pinecone, Weaviate, Qdrant, Milvus, Chroma, Zilliz, Vespa, Marqo, Elasticsearch vector features, Redis vector search, and **hnswlib** (`nmslib/hnswlib`)—a header-only C++ HNSW implementation for efficient approximate nearest neighbor search.

**Open-source emphasis**: Vector search is one of the strongest open ecosystems. **Milvus**, **Qdrant**, **Weaviate**, **Chroma**, **Faiss**, **hnswlib**, and **pgvector** are production standards. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pinecone, Zilliz Cloud, Weaviate Cloud, Qdrant Cloud](https://www.pinecone.io/)**  
  Managed vector databases—hosted indexes, scaling, and APIs without operating the cluster yourself.

- **[Amazon OpenSearch Serverless vector, Azure AI Search, Google Vertex Vector Search](https://aws.amazon.com/opensearch-service/)**  
  Cloud-provider vector and hybrid search integrated with broader data platforms.

- **[Redis Enterprise, Elastic Cloud vector features, Marqo Cloud](https://redis.io/)**  
  Managed data platforms with vector index capabilities alongside keywords and other query types.

- **[Other commercial vector / AI search platforms](https://weaviate.io/)**  
  Additional hosted embedding stores and retrieval services.

## Open-Source GitHub Projects

### Vector Databases & Engines

- **[Milvus](https://github.com/milvus-io/milvus)**  
  Leading open-source vector database—scale-out ANN search, multiple index types, and a rich ecosystem (often paired with Zilliz commercial offerings).

- **[Qdrant](https://github.com/qdrant/qdrant)**  
  Open vector database written in Rust—filtering, payload storage, and strong performance for production RAG.

- **[Weaviate](https://github.com/weaviate/weaviate)**  
  Open vector search engine—modules for vectorization, hybrid search, and GraphQL APIs.

- **[Chroma](https://github.com/chroma-core/chroma)**  
  Open embedding database popular for LLM apps—simple developer UX and local-to-server paths.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open big-data serving engine—hybrid ranking, vectors, and large-scale search/recommendation workloads.

- **[LanceDB](https://github.com/lancedb/lancedb)**  
  Open embedded vector database built on Lance—analytics-friendly and developer-local workflows.

- **[Vald](https://github.com/vdaas/vald)**  
  Open distributed vector search on Kubernetes—gRPC-based ANN service design.

### Libraries & Indexes

- **[hnswlib](https://github.com/nmslib/hnswlib)**  
  Header-only C++ HNSW implementation—fast approximate nearest neighbor search widely embedded in other systems.

- **[Faiss](https://github.com/facebookresearch/faiss)**  
  Open library from Meta for efficient similarity search and dense vector clustering—CPU/GPU indexes.

- **[nmslib](https://github.com/nmslib/nmslib)**  
  Open non-metric space library—additional ANN algorithms beyond pure HNSW.

- **[Annoy](https://github.com/spotify/annoy)**  
  Open approximate nearest neighbors library from Spotify—memory-mapped trees for read-heavy search.

- **[ScaNN](https://github.com/google-research/google-research/tree/master/scann)**  
  Open vector search library from Google Research—high-performance ANN methods.

### Databases with Vector Extensions

- **[pgvector](https://github.com/pgvector/pgvector)**  
  Open vector similarity search extension for PostgreSQL—keep embeddings next to relational data.

- **[Redis Search / vector (open Redis Stack components)](https://github.com/RediSearch/RediSearch)**  
  Open search module capabilities including vector fields in Redis-oriented stacks.

- **[OpenSearch k-NN](https://github.com/opensearch-project/k-NN)**  
  Open k-NN plugin for OpenSearch—vector search on the OpenSearch engine.

### Additional Strong Open-Source Options

- **Scale-out vector DB**: Milvus or Qdrant.
- **Developer-friendly local/server**: Chroma or LanceDB.
- **Hybrid search platform**: Weaviate or Vespa.
- **Postgres-centric**: pgvector.
- **Embed in-process**: Faiss or hnswlib.
- **Composable stacks**: Embeddings model → Faiss/hnswlib or Qdrant/Milvus → RAG orchestrator (LangChain/LlamaIndex).
- Managed cloud vector DBs still lead for zero-ops scaling and enterprise SLAs.

**Frameworks for building custom systems**:  
**Qdrant** / **Milvus** / **Weaviate** for dedicated vector DB; **pgvector** when SQL locality matters; **Faiss**/**hnswlib** for embedded indexes; **Chroma** for quick LLM prototypes.  
Fully open vector search is production-proven from startups to large RAG deployments.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Approximate nearest neighbor search trades recall for speed—validate quality on your data. Embeddings can encode sensitive information; control access and retention like any personal data store.
- Open-source vector systems offer control and portability. Managed vector DBs shift operations to the vendor. Neither replaces good chunking, embedding choice, and evaluation of retrieval quality.

---

**Made for AI engineers, search teams, and builders of RAG and semantic applications.**  
Let's expand open vector search while recognizing the managed scale that leading commercial vector platforms deliver.
