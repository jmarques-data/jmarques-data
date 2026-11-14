<p align="center">
  <img src="assets/banner.png" alt="Juan Marques · IA, Dados e Automações" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/juanmarrques"><img src="https://img.shields.io/badge/LinkedIn-juanmarrques-0131cd?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/foco-IA%20%C2%B7%20Dados%20%C2%B7%20Automa%C3%A7%C3%B5es-0a1b52?style=flat-square" alt="Foco: IA, Dados e Automações">
</p>

Projetos práticos de **IA aplicada, dados e automação**. Todos com código aberto, dados fictícios e documentação em português e inglês.

## 🚀 Projetos

### 🤖 [Knowledge Base Vectorization](https://github.com/jmarques-data/knowledge-base-vectorization): assistente de suporte com RAG

<a href="https://github.com/jmarques-data/knowledge-base-vectorization"><img src="https://raw.githubusercontent.com/jmarques-data/knowledge-base-vectorization/main/docs/banner.png" alt="Knowledge Base Vectorization" width="100%"></a>

<a href="https://github.com/jmarques-data/knowledge-base-vectorization/actions/workflows/testes.yml"><img src="https://github.com/jmarques-data/knowledge-base-vectorization/actions/workflows/testes.yml/badge.svg" alt="Testes"></a> <img src="https://img.shields.io/badge/Python-3.10%2B-0131cd?style=flat-square" alt="Python 3.10+"> <img src="https://img.shields.io/badge/RAG-Claude-b9fc01?style=flat-square" alt="RAG com Claude"> <img src="https://img.shields.io/badge/license-MIT-0a1b52?style=flat-square" alt="MIT">

**Problema:** no suporte de TI, a solução de um chamado costuma estar escondida em POPs e tickets antigos, e procurar leva tempo.
**Solução:** o analista pergunta em português, o sistema encontra os trechos certos da base e o Claude responde com os passos, **citando a fonte** de cada informação.

```text
Pergunta → embedding → busca semântica no ChromaDB → trechos relevantes
         → Claude → resposta com os passos e as fontes [arquivo#trecho]
```

| | |
|---|---|
| **Stack** | Python · ChromaDB · all-MiniLM-L6-v2 · Claude (SDK `anthropic`) · pytest · GitHub Actions |
| **Destaques** | Resposta com citação das fontes · diz quando a base não tem a resposta · modo só busca, sem chave · 13 testes rodando no CI (Python 3.10 e 3.12) |
| **Experimente** | `python perguntar.py "Sistema não abre: host remoto não encontrado"` |
| **Próximos passos** | Chunking por seções do Markdown · remover trechos duplicados · medir a qualidade das respostas |

### 🧠 [Segundo Cérebro com IA](https://github.com/jmarques-data/segundo-cerebro-ia): sistema de organização com Claude Code

<a href="https://github.com/jmarques-data/segundo-cerebro-ia"><img src="https://raw.githubusercontent.com/jmarques-data/segundo-cerebro-ia/main/docs/banner.png" alt="Segundo Cérebro com IA" width="100%"></a>

<img src="https://img.shields.io/badge/Claude%20Code-template-0131cd?style=flat-square" alt="Claude Code template"> <img src="https://img.shields.io/badge/Markdown-only-0a1b52?style=flat-square" alt="Markdown"> <img src="https://img.shields.io/badge/license-MIT-0a1b52?style=flat-square" alt="MIT">

**Problema:** estudos, carreira e projetos espalhados na cabeça, em notas soltas e lembretes esquecidos.
**Solução:** um modelo de pastas Markdown com regras e comandos para o Claude Code capturar, organizar e revisar tudo junto com você.

| | |
|---|---|
| **Estrutura** | 8 áreas (inbox, projetos, skills, agents, vida pessoal, vida, carreira, vídeos) + arquivo morto |
| **Comandos** | `/capturar` · `/revisar-semana` · `/vagas-status` (versão em inglês: `/capture` · `/weekly-review` · `/jobs-status`) |
| **Regras da IA** | Escreve em português · pergunta antes de editar · nunca apaga arquivos · não registra dados sensíveis |
| **Experimente** | Copie a pasta `pt-BR/` (ou `en/`) e abra com o Claude Code |

## 🧰 Stack dos projetos

<img src="https://img.shields.io/badge/Python-0131cd?style=flat-square&logo=python&logoColor=b9fc01" alt="Python"> <img src="https://img.shields.io/badge/Claude-0131cd?style=flat-square&logo=anthropic&logoColor=b9fc01" alt="Claude"> <img src="https://img.shields.io/badge/Claude%20Code-0131cd?style=flat-square&logo=anthropic&logoColor=b9fc01" alt="Claude Code"> <img src="https://img.shields.io/badge/ChromaDB-0131cd?style=flat-square" alt="ChromaDB"> <img src="https://img.shields.io/badge/Embeddings-0131cd?style=flat-square" alt="Embeddings"> <img src="https://img.shields.io/badge/RAG-0131cd?style=flat-square" alt="RAG"> <img src="https://img.shields.io/badge/pytest-0131cd?style=flat-square&logo=pytest&logoColor=b9fc01" alt="pytest"> <img src="https://img.shields.io/badge/GitHub%20Actions-0131cd?style=flat-square&logo=githubactions&logoColor=b9fc01" alt="GitHub Actions"> <img src="https://img.shields.io/badge/Markdown-0131cd?style=flat-square&logo=markdown&logoColor=b9fc01" alt="Markdown"> <img src="https://img.shields.io/badge/Git-0131cd?style=flat-square&logo=git&logoColor=b9fc01" alt="Git">

---

<sub>🇺🇸 <b>In English:</b> hands-on open-source projects in applied AI, data and automation: a RAG-based IT support assistant (Python, ChromaDB, Claude) and a Claude Code second-brain template. Docs in Portuguese and English.</sub>
