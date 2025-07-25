# RAG Agent Course
RAG Agent 是一款結合檢索增強生成(Retrieval-Augmented Generation, RAG)與大型語言模型(Large Language Model, LLM)的智慧代理(AI Agent)，具備網路搜尋、私有知識檢索與迭代優化回答的能力。

## Workflow
<image src="https://raw.githubusercontent.com/SDPM-lab/rag-agent-course/refs/heads/main/docs/workflow.png" alt="workflow.png">


## Setup
### Environments
- python: 3.11

### Install
```bash
pip install langchain langgraph gradio langchain-community faiss-cpu langchain-openai pypdf
```

## Deploy 
### Docker
```bash
# run
docker-compose up -d --buildg
open http://localhost:18080

# check logs
docker-compose logs -f
```