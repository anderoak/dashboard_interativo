# Dashboard de Salários na Área de Dados 📊

Este é um projeto desenvolvido durante as quatro aulas da **Imersão Dados com Python** da Alura. O objetivo do projeto é criar um dashboard interativo para análise de dados salariais na área de tecnologia, utilizando **Streamlit**, **Pandas** e **Plotly**.

## 📋 Descrição do Projeto

O dashboard permite explorar dados salariais de profissionais da área de tecnologia, com filtros interativos para refinar a análise. Ele apresenta métricas principais, gráficos interativos e uma tabela detalhada dos dados filtrados.

### Funcionalidades

- **Filtros Interativos**:
  - Filtrar por ano, senioridade, tipo de contrato e tamanho da empresa.
- **Métricas Principais (KPIs)**:
  - Salário médio, salário máximo, total de registros e cargo mais frequente.
- **Gráficos Interativos**:
  - Top 10 cargos por salário médio.
  - Distribuição de salários anuais.
  - Proporção dos tipos de trabalho (presencial, remoto, híbrido).
  - Salário médio de Cientistas de Dados por país.
- **Tabela Detalhada**:
  - Exibição dos dados filtrados em formato tabular.

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Streamlit**: Framework para criação de dashboards interativos.
- **Pandas**: Manipulação e análise de dados.
- **Plotly**: Criação de gráficos interativos.

## 📂 Estrutura do Projeto

```
.
├── app.py               # Arquivo principal do Streamlit
├── data
│   ├── dados.csv         # Base de dados em formato CSV
│   └── README.md         # Instruções sobre a base de dados
├── images
│   └── logo.png          # Logo da empresa (exemplo)
├── requirements.txt      # Dependências do projeto
└── README.md             # Documentação do projeto
```

## 🚀 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Execute o aplicativo**:
   ```bash
   streamlit run app.py
   ```

Acesse o dashboard pelo navegador no endereço `http://localhost:8501`.

## 📝 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

