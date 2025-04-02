# --Introdu-o-ao-Machine-Learning-e-Kaggle

# 1. Escolha da base de dados

A base escolhida foi "Titanic - Machine Learning from Disaster", disponível no Kaggle: Kaggle Titanic. Essa base permite explorar os fatores que influenciaram a sobrevivência dos passageiros do Titanic.

# 2. Exploração da base de dados

O conjunto de dados contém informações como idade, sexo, classe do bilhete e tarifa paga pelos passageiros. O objetivo é entender quais fatores mais impactaram a sobrevivência e construir um modelo preditivo.

Principais perguntas de análise:

Quem tinha maior probabilidade de sobreviver?

Qual o impacto da classe social e do gênero na sobrevivência?

Como prever a sobrevivência com base nesses dados?

# 3. Proposta de análise com Machine Learning

a) Técnica escolhida

Para resolver esse problema, utilizaremos classificação, pois queremos prever se um passageiro sobreviveu ou não (variável binária). A primeira abordagem será com Regressão Logística, que é simples e interpretável. Também podemos testar modelos mais complexos, como Random Forest e XGBoost, para comparar resultados.

b) Etapas do processo

Pré-processamento:

Remover colunas irrelevantes (como nomes e números de bilhete);

Tratar valores ausentes (como idade e local de embarque);

Converter variáveis categóricas para formato numérico.

Treinamento do modelo:

Separar os dados em treino e teste;

Aplicar regressão logística e avaliar seu desempenho;

Comparar com modelos mais avançados.

Avaliação e interpretação:

Medir a precisão e recall do modelo;

Identificar os fatores mais relevantes para a sobrevivência.

# Conclusão

Este estudo visa entender os principais fatores que influenciaram a sobrevivência no Titanic e construir um modelo preditivo. A análise pode ajudar a responder perguntas sobre padrões sociais e melhorar a compreensão de modelos de classificação em Machine Learning.

