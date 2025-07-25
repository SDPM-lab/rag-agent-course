# RAG Agent Course
RAG Agent 是一款結合檢索增強生成(Retrieval-Augmented Generation, RAG)與大型語言模型(Large Language Model, LLM)的智慧代理(AI Agent)，具備網路搜尋、私有知識檢索與迭代優化回答的能力。

- [PPT](https://github.com/SDPM-lab/rag-agent-course/blob/main/docs/2025%E6%99%BA%E6%85%A7%E5%89%B5%E6%96%B0%E9%97%9C%E9%8D%B5%E4%BA%BA%E6%89%8D-%E6%89%93%E9%80%A0%E5%B1%AC%E6%96%BC%E8%87%AA%E5%B7%B1%E7%9A%84%E6%99%BA%E6%85%A7%20AI%20Agent%20%E6%87%89%E7%94%A8.pptx)

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