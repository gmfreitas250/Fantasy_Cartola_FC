# Cartola FC Fantasy Analysis

Este projeto foi desenvolvido para fazer a gestão de uma liga do cartolafc de um grupo de amigos. Nesse código realizo análise dos dados e métricas da liga, consolidando pontuações e escalações de jogadores, gerando arquivos de histórico para alimentar um power bi com os gráficos.
Além disso foi realizado uma simulação de montecarlo com base no histórico de cada jogador, para trazer uma probabilidade de cada um ficar no Z4.

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
   git clone https://github.com/gmfreitas250/Fantasy_Cartola_FC
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


