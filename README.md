# README: Análise de Vendas com Machine Learning

Objetivo Geral

O objetivo deste projeto é desenvolver e avaliar um modelo de Machine Learning de regressão para prever as vendas mensais de uma empresa de varejo e tecnologia. O modelo foi treinado com dados de transações de 2023, atuando como um protótipo para auxiliar a gestão no planejamento estratégico, otimizando a alocação de recursos e melhorando o fluxo de caixa da empresa.
Estrutura do Notebook
O notebook está organizado em seções lógicas para guiar a análise e a construção do modelo:
    • 1. Escopo, Objetivo e Definição do Problema: Detalha o propósito do projeto, a descrição do problema, a área de aplicação, o valor para o negócio, as premissas e os atributos do conjunto de dados.
    • 2. Reprodutibilidade e Ambiente: Configura o ambiente, instala as dependências necessárias e importa as bibliotecas, além de definir funções utilitárias e um transformador customizado para datas.
    • 3. Dados: Carga, Entendimento e Qualidade: Realiza o carregamento do dataset, analisa seu formato, tipos de dados e verifica a presença de valores ausentes.
    • 4. Análise Exploratória dos Dados (EDA): Explora o dataset para identificar padrões, distribuições e a relação entre as variáveis.
    • 5. Pré-processamento e Engenharia de Features: Prepara os dados para o treinamento do modelo, tratando valores ausentes, codificando variáveis categóricas e extraindo novas features de tempo.
    • 6. Modelagem e Otimização: Avalia diferentes modelos de regressão, incluindo uma linha de base (DummyRegressor), e otimiza seus hiperparâmetros usando técnicas avançadas.
Como Executar o Notebook
Este notebook foi construído para ser executado no Google Colab. Para reproduzir a análise, siga os passos abaixo:
    1. Abra o arquivo .ipynb no Google Colab.
    2. Execute todas as células sequencialmente. O código já inclui comandos para instalar as bibliotecas necessárias.
    3. A etapa de drive.mount é opcional, mas necessária caso você precise acessar arquivos salvos em seu Google Drive.
Dependências
As seguintes bibliotecas Python são utilizadas no projeto. Elas são instaladas automaticamente ao executar as células do notebook:
    • xgboost
    • lightgbm
    • pandas
    • numpy
    • matplotlib
    • seaborn
    • scikit-learn
    • scipy
Insights Esperados
Ao final da análise e modelagem, espera-se que o notebook forneça os seguintes insights:
    • Uma compreensão clara do comportamento de vendas da empresa ao longo de 2023, identificando picos e sazonalidades.
    • Uma comparação entre a performance dos modelos de Random Forest, XGBoost e LightGBM, mostrando qual deles é mais preciso.
    • A identificação do modelo com o menor erro (RMSE) e maior poder de explicação (R²), garantindo uma base sólida para a previsão de vendas futuras.

Conclusão
O projeto demonstrou a viabilidade e o valor de aplicar técnicas de Machine Learning para a previsão de vendas. A análise completa do notebook revela que o RandomForestRegressor foi o modelo mais eficaz, fornecendo as previsões mais precisas e apresentando a maior capacidade de explicar a variabilidade dos dados. Esse resultado não apenas valida a abordagem, mas também equipa a empresa com uma ferramenta poderosa para um planejamento estratégico mais preciso e uma tomada de decisão orientada por dados.
