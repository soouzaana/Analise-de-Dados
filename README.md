# Análise de Dados de Cancelamentos

<img src="assets/tela.png"><br>
Exemplo de aplicação do projeto

Este repositório contém um projeto de análise de dados focado em cancelamentos de clientes. O objetivo é  analisar os dados para obter insights relevantes, identificar as principais causas de cancelamento e propor ações de melhoria.

## Principais Objetivos

- Analisar os dados de cancelamentos de clientes.
- Criar gráficos e dashboards em Python para visualização dos dados.
- Identificar as principais causas de cancelamento.
- Propor ações de melhoria para reduzir a taxa de cancelamento.

## Estrutura do Projeto

- `inicial.ipynb`: Jupyter Notebook com a análise de dados.
- `cancelamentos.csv`: Arquivo CSV contendo os dados de cancelamentos.
- `cancelamentos_sample.csv`: Amostra dos dados de cancelamentos para testes e desenvolvimento.

## Tecnologias Utilizadas

- Python
- Jupyter Notebook
- Bibliotecas de análise de dados (como Pandas, NumPy, Matplotlib, Seaborn, etc.)


### Resultados

A análise revelou que a taxa de cancelamento de clientes é atualmente de **56%**. O projeto visa reduzir essa taxa para **18%** através da identificação de causas e implementação de melhorias. 

### Conclusões
A partir da análise dos dados por meio da visualização gráfica, foi possível concluir que:
- usuários do contrato mensal tendem a cancelar mais.
- todos os usuários que ligaram mais de 4 vezes para o call center cancelaram.
- usuários que atrasaram o pagamento mais de 20 dias, cancelaram.

### Soluções
Assim, para que ocorra uma redução da taxa de cancelamento as seguintes soluções devem ser tomadas:
- evitar o contrato mensal, incentivando os contratos anuais e trimestrais.
- criar um processo que quando um usuário ligar mais de 3 vezes para o call center, alerta vermelho.
- criar um alerta para quando o atraso do pagamento bater 15 dias, entrar em contato.