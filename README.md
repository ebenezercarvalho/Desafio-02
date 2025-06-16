# Análise de Evasão de Clientes - Telecom X

Este projeto realiza uma análise detalhada dos fatores que influenciam a evasão de clientes em uma empresa de telecomunicações, utilizando dados reais para identificar padrões e insights importantes para a retenção de clientes.

## Propósito da Análise

O objetivo principal deste projeto é identificar e analisar os principais fatores que contribuem para a evasão de clientes em uma empresa de telecomunicações. A análise visa:

- Identificar correlações entre características dos clientes e a probabilidade de cancelamento
- Analisar o impacto de diferentes serviços e planos na retenção de clientes
- Avaliar a influência do tempo de contrato e métodos de pagamento na fidelização
- Fornecer insights acionáveis para melhorar a retenção de clientes

## Estrutura do Projeto

```
.
├── telecom-x.ipynb          # Notebook principal com a análise
├── telecom_x.csv           # Dataset com os dados dos clientes
├── relatorio.md            # Relatório detalhado com os insights
├── dicionario.md           # Documentação das variáveis do dataset
├── requirements.txt        # Dependências do projeto
└── img/                    # Diretório com os gráficos gerados
```

## Principais Insights

### 1. Tempo de Contrato
- Clientes nos primeiros 5 meses de contrato apresentam maior probabilidade de cancelamento
- Necessidade de estratégias específicas para fidelização no início do contrato

### 2. Serviços e Evasão
- Clientes com serviço de fibra ótica tendem a cancelar mais
- Serviços adicionais como Online Security, Backup Online e Proteção ao Dispositivo reduzem a evasão
- Clientes sem suporte técnico apresentam maior taxa de cancelamento

### 3. Modelo de Assinatura e Pagamento
- Assinaturas mensais têm maior taxa de evasão que anuais
- Pagamento via cheque eletrônico está associado a maior taxa de cancelamento
- Débito automático (cartão ou conta) apresenta melhor retenção

### 4. Perfil do Cliente
- Clientes acima de 65 anos apresentam maior taxa de evasão
- Renda do cliente influencia na decisão de manter serviços adicionais

## Como Executar o Projeto

1. Clone este repositório
2. Crie um ambiente virtual Python:
   ```bash
   python -m venv .venv
   ```
3. Ative o ambiente virtual:
   - Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - Linux/Mac:
     ```bash
     source .venv/bin/activate
     ```
4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
5. Abra o notebook `telecom-x.ipynb` usando Jupyter Notebook ou Jupyter Lab:
   ```bash
   jupyter notebook
   ```

## Dependências

- pandas
- numpy
- matplotlib
- seaborn

## Visualizações

O projeto inclui diversas visualizações que podem ser encontradas no diretório `img/`, incluindo:
- Gráficos de distribuição de idade
- Análise de tempo de contrato
- Comparação de serviços e taxas de evasão
- Análise de métodos de pagamento
- Distribuição de tipos de assinatura

## Contribuição

Sinta-se à vontade para contribuir com este projeto através de:
- Sugestões de melhorias
- Correções de bugs
- Novas análises e visualizações
- Documentação adicional 