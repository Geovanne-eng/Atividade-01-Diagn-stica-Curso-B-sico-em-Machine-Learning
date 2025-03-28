# Atividade-01-Diagn-stica-Curso-B-sico-em-Machine-Learning
# 🤖 Atividade 01 – Diagnóstica | Curso: Básico em Machine Learning



## ✅ Questões e Respostas

### 1. O que é Machine Learning?

Machine Learning (ou Aprendizado de Máquina) é um campo da Inteligência Artificial que desenvolve sistemas capazes de aprender com dados, identificar padrões e tomar decisões ou realizar previsões sem serem explicitamente programados para isso. Ao invés de seguir regras fixas, os modelos "aprendem" com a experiência.

**Exemplo:** Um modelo pode aprender a prever o valor de um imóvel com base em dados anteriores como localização, metragem e número de quartos.

---

### 2. O que são conjunto de treinamento, validação e teste?

- **Treinamento (Training Set):** Onde o modelo aprende os padrões dos dados.
- **Validação (Validation Set):** Serve para ajustar hiperparâmetros e evitar o overfitting (quando o modelo "decora" os dados).
- **Teste (Test Set):** Avalia o desempenho final do modelo em dados nunca vistos antes, simulando o uso real.

**Exemplo:** Em um modelo que prevê se um e-mail é spam ou não, usamos parte dos dados para treinar, outra parte para ajustar, e uma terceira parte para verificar se ele generaliza bem.

---

### 3. Como lidar com dados ausentes em um conjunto de treinamento?

Existem várias estratégias:

- **Remoção de linhas ou colunas** com valores ausentes (se forem poucas).
- **Preenchimento com média, mediana ou moda**.
- **Modelos preditivos** para estimar valores ausentes com base em outras variáveis.
- **Algoritmos que lidam bem com dados ausentes**, como algumas árvores de decisão.

**Exemplo:** Se uma coluna de idade tiver valores ausentes, posso preenchê-los com a média da idade dos demais registros.

---

### 4. O que é uma matriz de confusão?

É uma tabela que mostra os acertos e erros de um modelo de classificação. Ela compara os valores **reais** com os valores **previstos** pelo modelo.

|                   | Previsto Positivo | Previsto Negativo |
|-------------------|-------------------|-------------------|
| **Real Positivo** | Verdadeiro Positivo (VP) | Falso Negativo (FN) |
| **Real Negativo** | Falso Positivo (FP) | Verdadeiro Negativo (VN) |

A partir dela, calculamos métricas como:

- **Acurácia**
- **Precisão**
- **Recall**
- **F1-Score**

**Exemplo:** Em um modelo de diagnóstico de câncer, a matriz de confusão ajuda a entender quantos casos o modelo acertou e onde errou.

---

### 5. Em quais áreas aplicar Machine Learning?

Algumas áreas interessantes para aplicar Machine Learning:

- **Saúde:** Diagnóstico de doenças, medicina personalizada.
- **Agricultura:** Previsão de safras, detecção de pragas.
- **Manufatura:** Manutenção preditiva e controle de qualidade.
- **Construção Civil:** Análise de riscos e otimização de cronogramas.
- **Psicologia e Terapia:** Identificação de padrões emocionais, suporte terapêutico automatizado.

**Exemplo pessoal:** Como psicanalista, vejo grande potencial no uso de ML para análise de fala e emoções em sessões terapêuticas.

---
