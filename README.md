# 🧹 Desafio de Limpeza de Dados — Tempo.csv

Este projeto tem como objetivo realizar o tratamento e análise exploratória de um conjunto de dados meteorológicos, com foco na preparação dos dados para uso em modelos preditivos (como prever se deve-se jogar ou não).

## 📄 Descrição do Dataset

O arquivo `tempo.csv` contém as seguintes colunas:

- **Aparência**: Condição do tempo (`sol`, `nublado`, `chuva`)
- **Temperatura**: Varia de -135 a 130°F *(valores fora disso são inválidos)*
- **Umidade**: Percentual de 0 a 100%
- **Jogar**: `sim` ou `nao`

## ✅ Etapas do Projeto

1. **Leitura e inspeção dos dados**
2. **Tratamento de valores ausentes (NAs)**
3. **Validação e limpeza de faixas numéricas**
   - Temperatura: mantidos valores entre -135 e 130°F
   - Umidade: mantidos valores entre 0% e 100%
4. **Padronização de textos**
   - `Aparência` convertida para letras minúsculas e sem espaços extras
5. **Visualização de dados**
   - Histogramas e gráficos de barras para entender a distribuição de umidade e temperatura por condição do tempo
6. **Agrupamentos com `groupby()` e estatísticas descritivas**

## 📊 Ferramentas Utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 🧠 Insights Relevantes

- Foram encontrados e corrigidos valores inválidos nas colunas de Temperatura e Umidade.
- A análise mostra como a condição do tempo influencia na decisão de jogar ou não.
- Gráficos comparativos de estatísticas de umidade por temperatura permitiram melhor compreensão dos padrões no conjunto.

## 🚀 Como Executar

```bash
pip install -r requirements.txt
jupyter notebook MyTime.ipynb
