# tagny-langchain-petprojects
Here are some hands-on projects I made while mastering langchain.

They are examples of LLMs applications such as RAG and AI Agents. They use locally-deployed LLM and free online API service plans such as Google AI Studio and GitHub Marketplace.

## Setup

## Platform

- OS: Ubuntu 24.04 WSL
- CPU: Core i9 24 cores
- RAM: 32 Gb
- Disk: ~500 Gb
- GPU: NVIDIA GeForce RTX 3080 16 Gb

### Python virtual environment

- Python 3.11.8 installed with pyenv 2.3.36
- Install poetry: `pip install -U poetry==2.1.3`
- create and activate environment: `eval $(poetry env activate)`
- install dependencies: `poetry install --no-root --with "dev"`