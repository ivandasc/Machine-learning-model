# Previsão de Infecção pelo Vírus da AIDS

Este projeto visa desenvolver um modelo de aprendizado de máquina para prever a infecção pelo vírus da AIDS com base em características e histórico médico dos pacientes. O modelo utiliza dados de saúde para classificar se um paciente está infectado ou não.

## Conjunto de Dados

Os dados estão disponíveis em quatro arquivos CSV:

- `AIDS_Classification.csv`
- `AIDS_Classification_5000.csv`
- `AIDS_Classification_15000.csv`
- `AIDS_Classification_50000.csv`

Cada arquivo contém informações sobre diferentes números de pacientes.

## Objetivo

Desenvolver um modelo de classificação binária para prever a infecção pelo vírus da AIDS utilizando características dos pacientes. As principais etapas incluem:

1. **Análise Exploratória dos Dados (EDA)**
2. **Pré-processamento de Dados**
3. **Treinamento do Modelo**
4. **Avaliação do Modelo**

## Métricas de Avaliação

O desempenho do modelo será avaliado utilizando as seguintes métricas:

- Acurácia
- Sensibilidade
- Especificidade
- Precisão
- Pontuação F1

## Estrutura do Projeto

- `previsao_aids.py`: Código Python para treinamento e avaliação do modelo.
- `notebooks/`: Notebooks Jupyter com análises exploratórias e visualizações.
- `data/`: Pasta contendo os arquivos CSV com os dados.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu_usuario/previsao_aids.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd previsao_aids
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Execute o script:
    ```bash
    python previsao_aids.py
    ```

## Resultados

Os resultados do modelo, incluindo acurácia, sensibilidade, especificidade e outros, são impressos no console. Além disso, gráficos e visualizações podem ser encontrados nos notebooks.

## Contribuições

Contribuições são bem-vindas. Por favor, envie um pull request ou abra um issue para discutir mudanças.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
