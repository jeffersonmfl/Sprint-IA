# Análise do Tempo de Espera em Hospital

Este projeto realiza a análise e modelagem preditiva do tempo de espera de pacientes em um hospital. O código inclui a geração de um dataset fictício, análise exploratória dos dados e a construção de modelos preditivos para prever o tempo de espera com base em várias características.

## Estrutura do Código

1. **Geração do Dataset**
   - Cria um dataset fictício com informações sobre pacientes, incluindo tempo de espera, número de médicos, hora de chegada, dia da semana e severidade.
   - O dataset é salvo em um arquivo CSV (`hospital_wait_times.csv`).

2. **Análise Exploratória dos Dados**
   - Carrega o dataset a partir do arquivo CSV.
   - Realiza análise estatística descritiva e visualização dos dados.
   - Gera gráficos para distribuição do tempo de espera, identificação de outliers e relação entre o número de médicos e o tempo de espera.

3. **Pré-processamento dos Dados**
   - Converte variáveis categóricas em numéricas.
   - Preenche valores nulos, se existirem.

4. **Modelagem Preditiva**
   - Cria e treina dois modelos preditivos:
     - **Regressão Linear**: Avalia a relação linear entre as variáveis independentes e o tempo de espera.
     - **Random Forest**: Utiliza um ensemble de árvores de decisão para prever o tempo de espera.
   - Avalia o desempenho dos modelos com métricas como Erro Quadrático Médio (MSE) e o coeficiente de determinação (R²).

5. **Importância das Variáveis**
   - Avalia e visualiza a importância das variáveis no modelo Random Forest.

## Requisitos

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Execução

1. Execute o script para gerar o dataset e salvar o arquivo `hospital_wait_times.csv`.
2. O script irá automaticamente carregar o dataset, realizar a análise exploratória, e treinar os modelos preditivos.
3. Gráficos e métricas de avaliação serão exibidos ao final da execução.

