# Curso_Danki_Code_Fernando_Feltrin_Projeto2_Classificador_Parte1Andre

# Classificador de Tumores de Câncer de Mama

## 📌 Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo de aprendizado de máquina capaz de classificar tumores de câncer de mama como benignos ou malignos. A abordagem utilizada baseia-se em redes neurais profundas para a análise de características extraídas de exames clínicos. Esta é a primeira parte do projeto realizado no curso da DIO pelo Profesor Fernando Feltrin

## 🎯 Objetivo
O principal propósito deste projeto é auxiliar profissionais da área da saúde na detecção precoce do câncer de mama, proporcionando uma ferramenta eficiente para apoiar diagnósticos médicos.

## 🗂 Dataset Utilizado
O conjunto de dados utilizado é o **Wisconsin Breast Cancer Dataset (WBCD)**, disponível no [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). Este dataset contém informações clínicas de células mamárias obtidas por meio de exames de biópsia.

### 📊 Características do Dataset
- **Quantidade de amostras:** 569
- **Classes:** 2 (Benigno e Maligno)
- **Número de atributos:** 30 (excluindo o identificador)

## 🛠 Tecnologias Utilizadas
- **Python**
- **TensorFlow/Keras**
- **Scikit-Learn**
- **Matplotlib/Seaborn** (para visualizações)
- **Pandas/Numpy** (para manipulação de dados)

## 📌 Como o Projeto foi Feito?
1. **Carregamento dos Dados**: O dataset foi carregado e analisado para verificar a distribuição das classes.
2. **Pré-processamento**:
   - Normalização dos dados.
   - Separação em conjuntos de treino e teste.
3. **Construção do Modelo**:
   - Implementação de uma rede neural profunda utilizando TensorFlow/Keras.
   - Configuração de camadas densas com funções de ativação adequadas.
   - Uso de métricas como acurácia, precisão e recall para avaliar o desempenho.
4. **Treinamento e Validação**:
   - O modelo foi treinado utilizando o conjunto de treinamento e validado com os dados de teste.
5. **Avaliação do Desempenho**:
   - Cálculo da matriz de confusão, precisão, recall e F1-score.
   - Visualização da evolução da perda e acurácia durante o treinamento.

## 🚀 Como Executar o Projeto?
### 1️⃣ Pré-requisitos
Antes de rodar o projeto, certifique-se de ter as seguintes bibliotecas instaladas:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

### 2️⃣ Rodando o Script
Execute o script principal para treinar o modelo:
```bash
python main.py
```

## 📊 Métricas de Desempenho
Após o treinamento, o modelo foi avaliado utilizando diversas métricas:
RELATÓRIO FINAL (MÉTRICAS DE AVALIAÇÃO)
---------------------------------------
- **Acuracia Final:** 96.24%
- **Acurácia Geral:** 96.0%
- **Acurácia (Média U10):** 96.0%
- **Acurácia (Treinamento):** 96.0%
- **Acurácia (Validação):** 98.0%
- **Taxa de Perda:** 0.05%
- **Taxa de Perda (Validação):** 0.1%
- **Precisão:** 100.0%
- **Precisão (Validação):** 98.0%
- **Recall:** 99.0%
- **Recall (Validação):** 95.0%
- **F1 Score:** 99.0%
- **F-Measure:** 99.0%
- **F1 Score (TP, FP, TN, FN):** 97.0%
- **Taxa de Aprendizado:** 9.999999974752427e-07
- **Sensibilidade:** 97.0%
- **Especificidade:** 96.0%
- **Acurácia da Matriz de Confusão:** 96.0%
- **Taxa de Verdadeiros Positivos:** 99.0%
- **Taxa de Verdadeiros Negativos:** 98.0%
- **Taxa de Falsos Positivos:** 2.0%
- **Taxa de Falsos Negativos:** 1.0%
- **Dados Inválidos:** 1.0%

## 🔍 Visualizações Geradas
- Gráficos de perda e acurácia durante o treinamento.
- Matriz de confusão para análise de erros.
- Distribuição das classes no dataset.

## 📌 Conclusão
O modelo desenvolvido obteve uma boa performance na classificação dos tumores de câncer de mama, demonstrando a viabilidade do uso de redes neurais para este tipo de problema. Ainda assim, melhorias podem ser feitas, como ajuste fino dos hiperparâmetros e o uso de técnicas avançadas de aumento de dados.

## 🤝 Contribuições
Contribuições são bem-vindas! Se você deseja melhorar este projeto, fique à vontade para abrir um Pull Request ou relatar problemas na seção de issues.

## 📜 Licença
Este projeto está sob a licença MIT.

