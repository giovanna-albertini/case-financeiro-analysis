# Case Financeiro - Análise de Cotações de Ações 📈

Análise exploratória de dados financeiros com visualizações de cotações de ações, médias móveis e gráficos de candlestick.

## Sobre o Projeto

Este projeto realiza uma análise completa de dados de cotações de ações, incluindo:

- 📊 **Análise de Fechamento**: Tendências de preços ao longo do tempo
- 📈 **Médias Móveis**: Análise de média móvel de 5 e 30 dias para identificar tendências
- 📉 **Análise Mensal**: Variação dos preços por mês com boxplot
- 🕯️ **Gráfico Candlestick**: Visualização interativa com valores de abertura, fechamento, máxima e mínima

## Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Operações numéricas
- **Matplotlib** - Visualizações estáticas
- **Seaborn** - Visualizações estatísticas
- **Plotly** - Gráficos interativos (candlestick)

## Estrutura do Projeto

```
case-financeiro-analysis/
├── README.md
├── case_financeiro.py
└── requirements.txt (opcional)
```

## Como Usar

### Pré-requisitos

Instale as dependências necessárias:

```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

### Executar a Análise

1. Prepare seu arquivo de dados (formato .xlsx) com as colunas:
   - `Data`: Data da cotação
   - `Abertura`: Preço de abertura
   - `Maior`: Preço máximo do dia
   - `Menor`: Preço mínimo do dia
   - `Fechamento`: Preço de fechamento

2. Atualize o caminho do arquivo no script:
   ```python
   df = pd.read_excel('seu_caminho/dados.xlsx')
   ```

3. Execute o script:
   ```bash
   python case_financeiro.py
   ```

## Análises Realizadas

### 1. Análise de Fechamento
Gráfico de linha mostrando a evolução do preço de fechamento das ações ao longo do tempo.

### 2. Médias Móveis
Visualização de três linhas:
- Preço de fechamento real
- Média móvel de 5 dias (tendência de curto prazo)
- Média móvel de 30 dias (tendência de longo prazo)

### 3. Análise Mensal
Boxplot indicando a variação dos preços de fechamento para cada mês do ano.

### 4. Gráfico Candlestick
Visualização interativa com Plotly mostrando:
- Abertura, fechamento, máxima e mínima para cada dia
- Útil para análise técnica de ações

## Dados

Os dados incluem informações sobre:
- Data da cotação
- Preço de abertura, fechamento, máximo e mínimo
- Análise diária das flutuações de preço

## Resultados Esperados

Após executar o script, você terá:
- ✅ Múltiplas visualizações das tendências de preço
- ✅ Identificação de padrões e tendências com médias móveis
- ✅ Gráfico interativo candlestick para análise técnica
- ✅ Insights sobre variação mensal de preços

## Contribuições

Sinta-se à vontade para contribuir com melhorias, novas análises ou gráficos adicionais!

## Licença

Este projeto é de uso livre para fins educacionais e de pesquisa.

---

**Criado com ❤️ para análise de dados financeiros e cotações de ações**
