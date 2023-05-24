# Recomendação para Cross-Selling de Seguros

## 1. Sobre o Projeto
**Desafio:**
Identificar quais clientes de uma empresa de seguros de saúde têm maior propensão em adquirir um segundo tipo de seguro, especificamente um seguro automotivo. 
Vamos calcular a propensão de compra de cada cliente da base e retornar ao time de negócios uma lista priorizada, começando pelo cliente com maior propensão e seguindo até o cliente com menor propensão.

**Utilizaremos:**
- Dados públicos, disponíveis no [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction).
- Método CRISP-DM, seguindo os passos descritos na [seção 5](#planejamento-da-solução).

**Observação:** 
* Este é um projeto fictício, com o objetivo de desenvolver e demonstrar conhecimento nos estudos de Machine Learning, especificamente na criação de modelo de recomendação ranqueada para Cross-Selling.

## 2. Contato
- paulawehdorn@gmail.com
- [Portfólio](https://paulawehdorn.github.io/portfolio_projetos/)
- [LinkedIn](https://www.linkedin.com/in/paulawehdorn/)

## 3. Tecnologias Utilizadas
Modelos de classificação: KNN Classifier, ExtraTrees Classifier e XGBboost Classifier;
Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn;
Anaconda, VSCode e Jupyter Notebook;
Pickle, BorutaPy, Scipy;
CRISP-DM;
Git e Github.

## 4. Atributos
ATRIBUTO | DESCRIÇÃO | CONTEÚDO
-- | -- | --
id | ID exclusivo para o cliente | único para cada cliente
gender | Gênero do cliente | 'Male', 'Female' 
age | Idade do cliente | min: 20, max: 85
driving_license | Se o cliente tem ou não tem licensa | 0, 1
region_code | Código para a região do cliente | nunique  =  53
previously_insured | Se o cliente já possui Seguro de Veículo | 0, 1
vehicle_age | Idade do Veículo | > 2 Years, 1-2 Year, < 1 Year
vehicle_damage | Se o cliente teve seu veículo danificado no passado | 0, 1
annual_premium | O valor que o cliente pagou à empresa pelo seguro de saúde anual | min: 2,630.0, max: 540,165.0
policy_sales_channel | Código anônimo para o canal de divulgação ao cliente, por exemplo: correio, telefone, pessoalmente, etc. | min: 1.0, max: 163.0
vintage | Número de dias que o cliente se associou à empresa através da compra do seguro de saúde | min:10, max: 299
response | Se o cliente está interessado em contratar | 0, 1

## 5. Planejamento da Solução <a id="planejamento-da-solução"></a>

Utilizaremos o método CRISP-DM, pois ele ajuda a organizar as etapas do projeto desde a definição do problema até a implementação da solução.

#### As 6 fases principais do CRISP-DM são: 

1. Entendimento do problema;
2. Entendimento dos dados;
3. Preparação dos dados;
4. Modelagem;
5. Avaliação do modelo;
6. Deploy.

#### Dentro do projeto, vamos quebrá-las em 9 passos:

1. Passo 01: Descrição dos dados;
2. Passo 02: Feature engineering;
3. Passo 03: Filtragem de variáveis;
4. Passo 04: Análise exploratória de dados (EDA);
5. Passo 05: Preparação dos dados;
6. Passo 06: Seleção de variáveis;
7. Passo 07: Modelagem de Machine Learning;
8. Passo 08: Hyperparameter fine tuning;
9. Passo 09: Error translation and interpretation.

## 6. Performance do Modelo

## 7. Deploy do Modelo

## 8. Impacto Financeiro

## 9. Conclusão

## 10. Possíveis Melhorias
