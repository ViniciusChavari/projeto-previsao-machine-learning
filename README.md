# Machine Learning: Predição de Score de Crédito


> Desenvolvimento de um modelo de Inteligência Artificial para classificação de perfis de crédito (Good, Standard, Poor)
com base em histórico financeiro e comportamento do cliente.


## Objetivo do Projeto
O foco foi construir um pipeline de **Classificação** capaz de automatizar a análise de risco de crédito, permitindo 
que instituições financeiras tomem decisões mais rápidas e precisas, reduzindo a inadimplência.


## Stack Tecnológica & Modelagem
- **Linguagem:** Python
- **Manipulação de Dados:** Pandas
- **Machine Learning:** Scikit-Learn
- **Modelos Implementados:** - **Random Forest Classifier** (Modelo de Árvores de Decisão)
- **K-Nearest Neighbors (KNN)**
- **Métrica de Sucesso:** Acurácia de Classificação.
  
> Vencedor do Teste: Random Forest Classifier (Apresentou a melhor performance e acurácia na base de teste, sendo selecionado como o modelo principal para predição).

## Engenharia de Software e Processos
Para este modelo, apliquei o conceito de **Modularidade e Abstração**, garantindo um fluxo de dados limpo:
1. **Label Encoding:** Transformação de variáveis categóricas (textos) em numéricas para processamento do modelo.
2. **Train-Test Split:** Divisão da base em 75% para treino e 25% para teste, garantindo a validação real do aprendizado.
3. **Avaliação Comparativa:** Teste de múltiplos algoritmos para identificar o modelo com maior poder preditivo para este cenário.


## Valor para o Negócio
Este tipo de solução impacta diretamente no **ROI** (Retorno sobre Investimento) ao:
- Automatizar processos manuais de análise de crédito.
- Melhorar a **Experiência do Usuário (UX)** com respostas em tempo real.
- Minimizar riscos operacionais através de decisões baseadas em dados históricos.

---
**Vinicius de Araujo Chavari** *Estudante de ADS na Anhanguera | Focado em transformar dados em inteligência de negócio.*
