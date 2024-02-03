# DIO_Predicao_de_Alugueis_Azure_ML
Lab feito durante o Bootcamp: Microsoft Azure AI Fundamentals com realização da Dio, juntamente com a Microsoft. O primeiro projeto consiste na criação de um modelo preditivo utilizando o Azure Machine Learning.

### Objetivo
Seremos responsáveis por criar um modelo de predição de vendas de alugueis de bicicletas. Com isso iremos:
- Compreender padrões para aumentar os resultados da empresa
- Familiarização com o Azure Machine Learning

###  Ferramenta utilizadas
- Azure Machine Learning

### Preparando o ambiente

| Ferramenta | Link |
| --- | --- |
| Dataset |[Link para download](https://aka.ms/bike-rentals) |
| Azure Machine Learning | [Documentação](https://learn.microsoft.com/pt-br/azure/cloud-adoption-framework/ready/azure-best-practices/ai-machine-learning-mlops) |

Para iniciar o projeto será necessário uma conta no Portal da Azure e um grupo de recursos com Azure Machine Learning previamente configurados, além do dataset o qual iremos trabalhar.  O end-point também estão disponibilizados neste repositório em formato Json.

# Criação do modelo preditivo no Azure Machine Learning
Utilizaremos para isso o ML automatixado com as seguintes configurações:

   1. Método de treinamento
   
1.1 Treinar automaticamente

   2. Configurações básicas: dados preenchidos com descrição e tags.
   
   3. Tipos de dados
   
3.1 Selecionar tipo de tarefa: Regressão

3.2 Selecionar os dados: Adicionaremos o link do dataset

   4. Configurações de tarefas
   
4.1 Coluna de destino: Rentals

4.2 Exibir configurações de definição adicionais: desmarcar caixas e em modelos permitidos, selecionar Random Forest e Light GBM.

   5. Limites
   
5.1 Tipo de validação: divisão de validação de treinamento; Validação de percentual de dados :15%;

5.2 Dados de teste: divisão de teste de treinamento; Teste percentual de dados: 15%;

   6. Computação
   
Configuração padrão, prosseguir.

Por fim, enviamos para treinamento.

# Resultados
Em Tarefas9(jobs), escolhendo o método para análise e indo em métricas, podemos fazer uma análise dos dados apresentados.


 


