# Cartola FC Fantasy Analysis

Este projeto realiza análise de dados do **Cartola FC Fantasy**, consolidando pontuações de jogadores, gerando métricas e visualizações.

## Estrutura do Repositório

```
cartola-fc-fantasy/
│── README.md              # Explicação do projeto
│── requirements.txt       # Bibliotecas necessárias
│── notebooks/             # Notebooks Jupyter
│   └── Liga fantasy cartola fc - Otimizado.ipynb
│── src/                   # Código Python modular (em desenvolvimento)
│── data/                  # Pasta para dados locais (não versionados)
│── .gitignore             # Ignora arquivos pesados e temporários
```

## Como usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/cartola-fc-fantasy.git
   cd cartola-fc-fantasy
   ```

2. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate    # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Abra o Jupyter Notebook e rode a análise:
   ```bash
   jupyter notebook notebooks/
   ```

## Requisitos

As bibliotecas necessárias estão em `requirements.txt`.

## Próximos Passos

- Modularizar funções em `src/` para reutilização do código.
- Adicionar testes automatizados.
- Criar pipeline de atualização dos dados.

---
Projeto criado para análise e aprendizado de **dados esportivos com Python** ⚽📊
