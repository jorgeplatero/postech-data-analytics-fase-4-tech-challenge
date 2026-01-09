# Dashboard com Modelo Preditivo de Preço do Petróleo Brent

Este projeto consiste em um dashboard com insights para tomada de decisão no que diz respeito ao negócio do petróleo brent, o que inclui a implementação de um modelo de ML responsável pelo forecasting dos preços.

Os dados consumidos são tratados, processados e disponibilizados via script web scraping que consulta, semanalmente, os dados disponibilizada no endereço do IPEA.

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **Plataforma BI** | **Power BI** | `-` | Plataforma de BI utilizada para o desenvolvimento do dashboard |
| **Frontend/App** | **Streamlit** | `1.30.0` | Framework utilizado para o desenvolvimento do aplicativo web |
| **ML** | **Statsforecast** | `1.6.0` | Biblioteca utilizada para  o desenvolvimento do modelo |
| **Banco de Dados** | **PostgreSQL** | `16` | SGBD para armazenamento dos dados |
| **Linguagem** | **Python** | `-` | Linguagem de programação base para o desenvolvimento dos scripts |
| **Gerenciamento** | **Venv** | `-` | Gerenciador de ambientes virtuais para isolamento de dependências |

### Fontes de Dados

Os dados utilizados neste projeto estão disponibilizados no site do IPEA (Instituto de Pesquisa Econômica Aplicada), que disponibiliza os preços por barril do petróleo bruto tipo Brent, negociados em dias úteis, não incluindo despesa de frete e seguro. Também obteve-se a série histórica do preço do dólar para o mesmo período.

Link para a base de dados do IPEA: http://www.ipeadata.gov.br/ExibeSerie.aspx?module=m&serid=1650971490&oper=view

Link para a série histórica do dólar: http://www.ipeadata.gov.br/ExibeSerie.aspx?serid=38590&module=M

### Deploy

O projeto conta com um aplicativo web (MVP) desenvolvido com Streamlit e um dashboard Power BI que disponibiliza a série histórica, o forecast semanal outras métricas para análise e tomada de decisão. 

Link para o aplicativo (MVP): https://postechtechchallengefase4-ceqwpwmwrl4eucsnvjjsjm.streamlit.app/

Link para o dashboard: https://app.powerbi.com/view?r=eyJrIjoiYjcxNGZlNmYtMDI4OS00NmJiLTk3Y2EtMWMyZWEyZWJmMTA4IiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9

### Colaboradores

[Mateus Albuquerque](https://github.com/mateus-albuquerque)

[Adrielly Silva](https://github.com/adriellytsilva)
