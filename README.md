# 📊 Análise da Receita Tributária Brasileira (2002–2021)

Este projeto realiza uma análise exploratória da receita tributária brasileira no período de 2002 a 2021. O objetivo é compreender a evolução da arrecadação dos principais tributos, identificar tendências estruturais e conjunturais e avaliar o impacto de eventos econômicos relevantes sobre a arrecadação pública.

---

## 🎯 Objetivos

- Analisar a evolução histórica da receita tributária em valores absolutos.
- Avaliar a participação da União, estados e municípios na arrecadação.
- Investigar o comportamento de tributos específicos como PIS, COFINS, IRPJ, CSLL, IOF, ISS e tributos sobre o comércio exterior.
- Relacionar variações de receita a eventos econômicos (ex: crises, pandemia, políticas fiscais).
- Propor caminhos para expansão da análise com base em novos dados ou indicadores.

---

## 🧰 Tecnologias Utilizadas

- **Python 3.11.12**
- **Google Colab**
- **Bibliotecas**:
  - `pandas`
  - `matplotlib`
  - `numpy`

---

## 📁 Estrutura do Projeto

```plaintext
analise-da-receita-tributaria-brasileira/
├── data/                                     # Dados utilizados na análise
│   └── tabela_2_tributo_e_competencia.csv    
├── projeto_receita_tributaria.ipynb          # Notebook principal
├── images/                                   # Gráficos do projeto
│   └── geral
│   └── por_imposto
├── README.md                                 # Documentação do projeto
└── LICENSE                                   # Licença de uso
```

---

## 📈 Destaques da Análise

- A União concentra cerca de 74% da arrecadação tributária total no período analisado.
- O ICMS, de competência estadual, é o imposto com maior arrecadação individual.
- Tributos como IRPJ e CSLL mostraram forte sensibilidade a crises econômicas.
- O IOF teve comportamento oscilante, refletindo sua utilização como instrumento de política econômica.
- O impacto da pandemia foi visível em quase todos os tributos, com queda em 2020 e recuperação em 2021.

---

## 📌 Possibilidades de Expansão

- **Atualização com dados pós-2021**, para incluir o período pós-pandemia e reformas fiscais.
- **Correção dos valores pela inflação**, viabilizando comparações reais ao longo do tempo.
- **Desagregação regional**, caso sejam disponibilizados dados por estado ou município.
- **Integração com indicadores socioeconômicos**, como PIB per capita, IDH ou população.
- **Modelagem preditiva**, utilizando séries temporais para estimar arrecadações futuras.

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Giselle-Del-Sent/analise-da-receita-tributaria-brasileira.git
   cd analise-da-receita-tributaria-brasileira

## 📚 Referências

- [Carga Tributária - Dados Abertos](https://dados.gov.br/dados/conjuntos-dados/carga-tributria): Conjunto de dados fornecido pela Receita Federal, disponível no portal dados.gov.br, contendo informações detalhadas sobre a arrecadação tributária brasileira com base em diferentes categorias econômicas e tipos de tributos.

---

## 📃 Licença

Este projeto é de livre uso para fins educacionais e portfólio. Caso deseje utilizar em outras finalidades, entre em contato com a autora.

---

## ✍️ Autoria

Projeto desenvolvido por [Giselle Del Sent](https://github.com/Giselle-Del-Sent) como parte de sua formação prática em Análise de Dados com Python.
