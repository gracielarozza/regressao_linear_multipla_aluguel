# Regressão Linear - Previsão de Aluguel de Imóveis

O objetivo deste projeto é desenvolver um modelo de **regressão linear múltipla** para prever o valor do aluguel de imóveis residenciais.

A previsão será feita com base em características estruturais dos imóveis, como:
- Metragem
- Número de quartos
- Banheiros
- Suítes
- Vagas de garagem
- Valor do condomínio

O desempenho do modelo deve ser avaliado principalmente pelo **coeficiente de determinação (R²)**.  
Essa métrica mostra a proporção da variação no valor do aluguel que pode ser explicada pelas variáveis do modelo.

## Bibliotecas utilizadas

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## Arquivos

- **`regressao_linear_aluguel.ipynb`** - Notebook principal do projeto, que contém todas as etapas realizadas.

## Conclusões

Houve uma pequena melhora no desempenho do modelo ao utilizar a regressão linear múltipla, em relação à regressão linear simples. O R² aumentou de **0.52 no modelo simples** para **0.61 no modelo múltiplo**, indicando que o segundo foi capaz de explicar uma proporção maior da variação no valor do aluguel.

Essa melhora sugere que informações relevantes foram adicionadas no segundo modelo. Porém, como o aumento não foi tão evidente, é importante **avaliar outras métricas de desempenho além do R²** antes de tomar uma decisão final.

É válido lembrar que dependendo do objetivo da análise, o modelo mais simples poderia ser suficiente.

Como próximos passos, seria interessante incluir variáveis que podem ter impacto no valor do aluguel, como:
- Idade do imóvel;
- Localização (bairro, proximidade de centros comerciais ou transporte);
- Estrutura do condomínio (área de lazer, elevador, portaria 24h);
- Estado de conservação do imóvel.

Análises com essas variáveis podem melhorar ainda mais o modelo, resultando em uma previsão mais precisa.

## Autora

**Graciela Rozza**  
Projeto desenvolvido como parte dos estudos em **Ciência de Dados**, com foco no **tratamento de dados, análise exploratória e modelagem preditiva**.

## Licença

MIT
