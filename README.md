# Mini Motor de Busca Semântico — Notícias Econômicas

Este projeto foi desenvolvido como parte do Desafio Técnico para Estágio em Ciência de Dados do FGV IBRE.

O objetivo é construir um mini motor de busca semântico aplicado a notícias econômicas fictícias sobre a economia brasileira.

O projeto cobre três etapas principais:

1. Limpeza e tratamento de textos brutos;
2. Geração de embeddings com modelos de linguagem;
3. Busca semântica por similaridade de cosseno.

---

## Estrutura do Projeto

```txt
desafio-busca-semantica-fgv/
│
├── dados/
│   ├── noticias_brutas.json
│   └── noticias_limpas.json
│
├── src/
│   ├── limpeza.py
│   ├── embeddings.py
│   └── busca.py
│
├── main.py
├── requirements.txt
└── README.md