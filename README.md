# 📊 Teste_Lappis: Análise de Projetos de Investimento - DF

Análise de dados de projetos de investimento do Distrito Federal (DF) utilizando a API do ObrasGov.br.

## 📝 Sobre o Projeto

Este projeto demonstra habilidades em Análise e Engenharia de Dados ao coletar, processar e analisar dados de obras públicas no Distrito Federal diretamente da API oficial do governo (`ObrasGov.br`). O objetivo é transformar dados brutos em insights estruturados e visualmente representados.

## 🚀 Como Usar

### Instalação

Clone o repositório e instale as dependências necessárias:

```bash
pip install pandas requests sqlalchemy matplotlib seaborn jupyter
````

### Execução

Após a instalação, inicie o Jupyter Notebook e execute o arquivo de análise principal:

```bash
jupyter notebook analise_dados.ipynb
```

## ✨ Funcionalidades

  * **Coleta de Dados:** Extração direta de dados atualizados da API ObrasGov.br.
  * **Tratamento e Limpeza:** Processamento e normalização dos dados brutos.
  * **Armazenamento:** Persistência dos dados estruturados em um banco de dados **SQLite**.
  * **Análise Visual:** Geração de gráficos e estatísticas para facilitar a interpretação dos resultados.
  * **Exportação:** Salvamento dos dados limpos em formato **CSV** e no banco de dados.

## 📁 Estrutura do Projeto

```text
projeto/
├── analise_dados.ipynb    # Notebook principal com o ETL e Análise
├── obras_df.db            # Banco de dados SQLite gerado
├── dados_projetos_df.csv  # Exportação dos dados tratados
└── requirements.txt       # Lista completa de dependências
```

## 📈 Resultados Principais (Amostra)

| Métrica | Valor | Detalhes |
| :--- | :--- | :--- |
| **Projetos Analisados** | 10 | Projetos no DF. |
| **Projetos Ativos** | 8 (80%) | Proporção de projetos em andamento. |
| **Empregos Gerados** | 30 | Total de empregos diretos estimados. |
| **Pessoas Beneficiadas** | 385 | População impactada pelos projetos. |
| **Período de Análise** | 2021-2028 | Intervalo de tempo dos projetos analisados. |

## 💻 Tecnologias

  * **Python**
  * **Pandas** (Manipulação de dados)
  * **Requests** (Consumo da API)
  * **SQLite** (Armazenamento de dados)
  * **Matplotlib/Seaborn** (Visualização de dados)

## 🔜 Próximos Passos

  * **Dashboard Interativo:** Criar um dashboard dinâmico (ex: com Plotly/Dash ou Streamlit) para visualização em tempo real.
  * **Monitoramento Contínuo:** Implementar rotinas de atualização periódica e monitoramento da API.
  * **Análise Multi-Estadual:** Expandir a coleta e análise para projetos em outros estados do Brasil.

<!-- end list -->

```
```
