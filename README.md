# Classificação de Sentimento Binário com KNIME

Projeto de classificação binária de sentimentos (positivo/negativo) utilizando o KNIME Analytics Platform, com base no dataset **Sentiment Labelled Sentences** da UCI Machine Learning Repository.

## Dataset

**Sentiment Labelled Sentences (UCI)** — frases curtas rotuladas como positivas ou negativas, extraídas de reviews do Amazon, Yelp e IMDb.

- Fonte: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences)
- Referência: Kotzias, D. (2015). *Sentiment Labelled Sentences* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C57604

## Pipeline

1. Leitura e verificação dos dados
2. Pré-processamento (tokenização, lowercase, remoção de stopwords, lemmatização vs stemming)
3. Representação vetorial (Bag-of-Words)
4. Divisão treino/teste
5. Treinamento dos modelos
6. Avaliação (acurácia, precisão, recall, F1, matriz de confusão)
