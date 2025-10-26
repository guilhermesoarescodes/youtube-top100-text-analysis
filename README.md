## 📘 Projeto Final | Análise e Modelagem de Dados das Músicas Mais Populares do YouTube em 2025

### 🔹 Descrição do Projeto

O objetivo deste projeto foi analisar padrões textuais presentes nos títulos e descrições das 100 músicas mais populares do YouTube em 2025. Buscou-se identificar como características linguísticas — como número de palavras, presença de emojis e tamanho dos textos — se relacionam com o comprimento dos títulos.

O projeto inclui **limpeza de dados, feature engineering, análise exploratória e modelagem de regressão**, com foco em automação e reprodutibilidade.

---

## 🎯 Principais Etapas

1. **Leitura e limpeza do dataset**: remoção de duplicatas, valores nulos e links irrelevantes.  
2. **Análise exploratória**: visualização de distribuições, tamanhos médios de textos e palavras mais frequentes.  
3. **Feature Engineering**: criação de métricas como contagem de palavras e presença de emojis.  
4. **Modelagem preditiva**: regressão (Random Forest) para prever o tamanho dos títulos.  
5. **Avaliação do modelo**: métricas R², RMSE, MAE, análise de resíduos e correlação.  

---

## ⚙️ Requisitos

- Python 3.8+  
- Bibliotecas Python:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - re (regex)

> É recomendado criar um ambiente virtual antes de instalar as bibliotecas:

```python -m venv venv
# Linux / macOS
source venv/bin/activate
# Windows
venv\Scripts\activate
pip install -r requirements.txt

---

🚀 Uso

**1. Clone o repositório**

git clone https://github.com/guilhermesoarescodes/youtube-top100-text-analysis.git
cd youtube-top100-text-analysis

---

**2. Abra e execute o notebook youtube_top100_analysis.ipynb no Google Colab ou Jupyter Notebook.
O notebook realiza automaticamente:**

* Limpeza do dataset

* Cálculo de métricas textuais

* Visualizações exploratórias

* Treinamento e avaliação do modelo de regressão

* Visualização de resíduos e comparação de valores reais vs. previstos

---

📊 **Resultados do Modelo**

O modelo Random Forest apresentou desempenho satisfatório:

Métrica      | Valor
------------ | -----
R²           | 0,52
Correlação   | 0,74
RMSE         | 12,78
MAE          | 7,93
Média dos resíduos | -0,03

**Interpretação:**
O modelo captura mais da metade da variabilidade do tamanho dos títulos, com erros médios controlados e sem viés significativo.

---

💡 **Possíveis Melhorias**

* Aplicar técnicas avançadas de Processamento de Linguagem Natural (NLP)

* Realizar análise de sentimentos e frequência de palavras-chave

* Utilizar embeddings de texto (Word2Vec, BERT) para melhorar features

* Expandir o dataset para diferentes períodos ou gêneros musicais

* Testar outros modelos de regressão ou algoritmos de ensemble mais complexos

---

📌 **Conclusão**

O projeto demonstra como transformar dados textuais em informações numéricas e gerar insights relevantes sobre padrões de linguagem.
O grande valor está no pipeline automatizado, claro e replicável, capaz de transformar dados brutos em conhecimento prático.

---

📝 **Licença**

MIT License © Guilherme Soares







