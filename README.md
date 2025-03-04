# Projeto-Engenharia-de-dados

*Bem-vindo ao **Projeto de Engenharia de Dados** da **Pós Graduação em Engenharia de dados e IA da Faculdade Anhanguera**!* 

- Este repositório foi construído para demonstrar os conhecimentos adquiridos nas Linguagens Python, SQL e Git/GitHub, com foco em engenharia de dados.

![image](https://github.com/user-attachments/assets/8c2059af-1081-4b86-aa1a-65c696bb9261)

- Aqui os dados são divididos em 3 camadas: Bronze, Silver e Gold(Arquitetura Medalhão).
![image](https://github.com/user-attachments/assets/70b5e1eb-0259-4f24-8ef4-380167229c5c)

- **Landing Layer**: Serve como uma ponte para receber os dados(json,csv), quando não for possível recebe-los de forma direta na Camada Bronze(Ex.: aplicação web)
- Camada Bronze: dados brutos
- Camada SIlver: dados refinados, dicionário dos dados presente, colunas padronizadas, regras para data/hora, registros únicos.
- Camada Gold: Dados prontos para consumo e visualização/geração de dashboards.

- Passo 1: Simularemos uma exportação do SAP, arquivos CSV(pasta  local) recebidos na **Landing Layer**.
- Passo 2: Processar e salvar em uma tabela(Camada Bronze).
- Passo 3: Enriquecer os dados e disponibilizar na Camada Silver.
- Passo 4: Transformar e disponibilzar na Camada Gold.

