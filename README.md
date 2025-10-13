# 📊 Projeto: Integração com API de Dados abertos da Câmara dos Deputados / IBGE

Projeto Final Tiller — Pipeline Python para Dados via APIs

Este projeto realiza a ingestão de dados abertos da **Câmara dos Deputados**  e do **IBGE** diretamente no Databricks, com tratamento das informações e armazenamento em tabelas para análises posteriores.

---

## 📌 Fontes de Dados

Todos os dados foram extraídos do site de dados abertos da Câmara: 
https://dadosabertos.camara.leg.br/

**Endpoints utilizados:**

- Deputados: https://dadosabertos.camara.leg.br/api/v2/deputados
- Proposições: https://dadosabertos.camara.leg.br/api/v2/proposicoes
- Eventos: https://dadosabertos.camara.leg.br/api/v2/eventos
- Despesas: https://dadosabertos.camara.leg.br/swagger/api.html?tab=staticfile (Realizado Download do Documento)
- Estados: https://servicodados.ibge.gov.br/api/v1/localidades/estados


**Documentações:**

Documentações disponíveis em:
https://dadosabertos.camara.leg.br/swagger/api.html?tab=api

---

## ⚙️ Pré-requisitos

- **Databricks** configurado
- **Runtime com PySpark** habilitado

**Bibliotecas necessárias:**


Todas disponíveis no nb_parametros.


🚀 Execução

- Criar um Notebook no Databricks.
- Copiar o código do projeto para o Notebook.
- Executar o arquivo Bronze_ para ingestão e tratamento dos dados da CVM.
- Executar o arquivo silver para limpeza
- Executar arquivos da camada gold.

## Modelo

<img width="1066" height="648" alt="Modelo Tiller" src="https://github.com/user-attachments/assets/0c36e5d8-cac3-4b53-a86a-25470cd1c03d" />



## 📄 Licença
Este projeto utiliza dados públicos disponibilizados sob licença aberta.
O uso é livre, respeitando as condições dos endpoints consultados.
