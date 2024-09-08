# Anallisando Tendências do mercado de commodities

## O objetivo do projeto é analisar a tendência de um commoditie, dados as notícias e indicativos técnicos (médias móvel exponêncial e simples), foram utilizadas técnicas de PLN como **sumarização de textos**,**análise de sentimentos** e **extração de informação**.

## Recurso utilizados:
- **LLM**: Gemini;
- **APIs**: Langchain e News Api;

## Funcionalidades:
- **Análise de Artigos**: A News API é responsável por fornecer as notícias para o modelo analisar se é positiva ou negativa;
- **Análise dos Indicativos:** Médias móveis exponênciais e simples são fornecidas para o modelo analisar;
- **Análise final**: O modelo recebe um prompt que recebe as médias e as notícias, o critério estabelecido foi de 85% de relevâncias para as notícias e de 15% para os indicativos. 
