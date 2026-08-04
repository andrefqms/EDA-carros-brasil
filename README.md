# 🚗 Análise Exploratória de Dados: Preços de Carros no Brasil (FIPE)

## 📌 Sobre o Projeto

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** sobre os preços médios de veículos vendidos no Brasil utilizando dados da **Tabela FIPE**.

O objetivo principal é investigar estatisticamente como diferentes características dos veículos influenciam o preço médio, explorando relações entre variáveis como:

- Idade do veículo;
- Marca;
- Modelo;
- Tipo de combustível;
- Tipo de câmbio;
- Tamanho do motor;
- Ano de referência;
- Evolução temporal dos preços.

A análise foi desenvolvida utilizando **Python no Google Colab**, aplicando técnicas de estatística descritiva, visualização de dados e análise exploratória.

# 📊 Dataset

## Fonte dos dados

Os dados foram extraídos da **[Tabela FIPE](https://www.kaggle.com/datasets/vagnerbessa/average-car-prices-bazil/)**, referência utilizada no mercado brasileiro para estimativa de preços de veículos.

O dataset contém preços médios mensais de veículos entre:

- **Janeiro de 2021**
- **Janeiro de 2023**

Cada linha representa o preço médio de um determinado veículo em um mês específico.

---

## Variáveis utilizadas

| Variável | Descrição |
|---|---|
| `year_of_reference` | Ano de referência da consulta FIPE |
| `month_of_reference` | Mês de referência do preço |
| `fipe_code` | Código identificador do veículo na FIPE |
| `brand` | Marca do veículo |
| `model` | Modelo do veículo |
| `fuel` | Tipo de combustível |
| `gear` | Tipo de câmbio |
| `engine_size` | Cilindrada do motor (cm³) |
| `year_model` | Ano do modelo do veículo |
| `avg_price_brl` | Preço médio do veículo em reais (R$) |


# 📜 Licença

Este projeto utiliza dados públicos provenientes da Tabela FIPE para fins educacionais e acadêmicos.
