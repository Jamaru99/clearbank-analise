# Análise Financeira com Python - ClearBank

## Descrição do Projeto
Este projeto é a solução do desafio final de Análise de Dados da Rocketseat. Ele consiste em um notebook Python que lê, valida e limpa um histórico de transações bancárias em formato CSV. A partir desses dados, o código calcula métricas financeiras mensais e identifica automaticamente movimentações suspeitas.

## Como Executar
1. Faça o clone ou download deste repositório.
2. Abra o arquivo `desafio-final.ipynb` utilizando o **Google Colab** ou um **Jupyter Notebook** local.
3. Certifique-se de que o arquivo `transacoes.csv` esteja na mesma pasta/diretório do notebook.
4. Execute todas as células em ordem (de cima para baixo).

## Saídas Geradas
Ao rodar todas as células do notebook, o script gera três resultados principais:
1. **Relatório no Terminal:** Um resumo impresso na tela contendo a contagem de linhas processadas, as métricas agrupadas por mês (saldo, total de crédito/débito, médias) e a lista de transações suspeitas.
2. **Arquivo `relatorio.json`:** Um arquivo gerado automaticamente com a estrutura de dados consolidada da análise.
3. **Arquivo `grafico.png`:** Uma imagem contendo o gráfico de barras que visualiza o saldo mensal gerado pela análise.