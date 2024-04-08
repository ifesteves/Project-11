# Projeto de Estudo de Caso Analítico - Model Fitness

## Descrição do Projeto
Este projeto visa desenvolver uma estratégia de interação com os clientes da rede de academias Model Fitness baseada em análise de dados. A partir dos dados disponibilizados, o objetivo é prever a probabilidade de rotatividade dos clientes para o próximo mês, elaborar retratos de usuários típicos, analisar os principais fatores que impactam a rotatividade e fornecer recomendações para melhorar o serviço aos clientes.

## Conjuntos de Dados
Os dados utilizados para análise estão disponíveis no arquivo CSV:

- `gym_churn_us.csv`: Contém informações sobre rotatividade de clientes e características dos mesmos.

**Caminho do arquivo:** `/datasets/gym_churn_us.csv`

## Passo a Passo do Projeto

### Passo 1: Análise Exploratória de Dados (AED)
- Verificar se há características ausentes e analisar estatísticas descritivas dos dados.
- Observar as médias das características em dois grupos: para os clientes que ficaram e os que saíram.
- Criar histogramas e distribuições de características para os clientes que saíram e os que ficaram.
- Construir e exibir a matriz de correlação.

### Passo 2: Construção de um Modelo de Predição de Rotatividade
- Dividir os dados em conjuntos de treinamento e validação.
- Treinar modelos de regressão logística e floresta aleatória.
- Avaliar a acurácia, precisão e sensibilidade dos modelos utilizando os dados de validação.

### Passo 3: Criação de Agrupamentos de Clientes
- Padronizar os dados.
- Construir um dendrograma para estimar o número de agrupamentos.
- Treinar o modelo de agrupamento com o algoritmo K-means.
- Analisar os valores médios das características para os agrupamentos.
- Fazer distribuições de características para os agrupamentos.
- Calcular a taxa de rotatividade para cada agrupamento.

### Passo 4: Conclusões e Recomendações
- Tirar conclusões sobre os principais fatores que impactam a rotatividade.
- Formular recomendações para melhorar a estratégia de interação e retenção de clientes.

## Instruções para Execução
1. Baixe o arquivo CSV contendo os dados fornecidos.
2. Realize a análise exploratória de dados conforme descrito no Passo 1.
3. Construa e avalie os modelos de predição de rotatividade conforme descrito no Passo 2.
4. Crie agrupamentos de clientes e analise os resultados conforme descrito no Passo 3.
5. Chegue a conclusões e recomendações com base nos resultados obtidos no Passo 4.

## Considerações Finais
Este projeto visa auxiliar a Model Fitness na compreensão dos fatores que impactam a rotatividade de clientes e na elaboração de estratégias eficazes para retenção e interação com os mesmos. As análises e recomendações fornecidas têm como objetivo melhorar a experiência dos clientes e contribuir para o sucesso da rede de academias.



