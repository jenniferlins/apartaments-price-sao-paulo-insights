# Projeto Aplicado I: Análise Preditiva do Mercado Imobiliário (SP)

## 📌 Identificação
* **Disciplina**: Projeto Aplicado I
* **Instituição**: Universidade Presbiteriana Mackenzie
* **Grupo**: 2A - Grupo 13
* **Integrante**: Jennifer Lins (RA: XXXXXXXX)

---

## 🏢 A Empresa-Alvo: ZAP Imóveis
A **ZAP Imóveis** é a maior plataforma de classificados online de imóveis do Brasil. Operando sob o ecossistema da OLX Brasil, a empresa é uma *PropTech* (Property Technology) líder que utiliza dados para conectar proprietários, imobiliárias e compradores.

* **Abrangência**: Presença em todo o território nacional, com foco estratégico em grandes metrópoles como São Paulo e Rio de Janeiro.
* **Volume de Dados**: Gerencia mais de 12 milhões de anúncios e possui parceria com mais de 45.000 clientes profissionais.
* **Inteligência de Mercado**: Através do braço **DataZAP**, a empresa fornece análises avançadas para incorporadoras. Além disso, é co-responsável pelo **Índice FipeZAP**, o principal indicador econômico de preços de venda e locação do país.

---

## 🎯 O Projeto
Este projeto tem como objetivo realizar uma exploração profunda e extrair *insights* estratégicos sobre o mercado de apartamentos na cidade de São Paulo, utilizando técnicas de Ciência de Dados para entender a dinâmica de preços e características dos imóveis.

### Conexão com ODS (UNESCO)
Este estudo está alinhado ao **ODS 11: Cidades e Comunidades Sustentáveis**. Ao analisar dados habitacionais, o projeto contribui para a compreensão da oferta imobiliária e do acesso à moradia em uma das maiores metrópoles do mundo, auxiliando na transparência de informações sobre o custo de vida urbano.


---

## 📊 Dataset
Os dados utilizados foram extraídos do dataset [Discover São Paulo: Apartment Prices Insights](https://www.kaggle.com/datasets/marcelobatalhah/discover-so-paulo-apartment-prices-insights) via Kaggle. O conjunto de dados compreende aproximadamente 28.000 registros de apartamentos à venda na capital paulista, coletados em novembro de 2024.

### Dicionário de Dados (Metadata)
| Variável | Descrição |
| :--- | :--- |
| `id` | Identificador único do imóvel (usado para compor a URL do anúncio). Ex: https://www.zapimoveis.com.br/imovel/venda-apartamento-4-quartos-paraiso-zona-sul-sao-paulo-sp-340m2-id-**{id}**/ |
| `created_date` | Data de publicação do anúncio. |
| `price` | Valor de venda anunciado (em R$). |
| `below_price` | Indicador booleano (True/False) para imóveis abaixo da média da região. |
| `area` | Área útil do imóvel em metros quadrados (m²). |
| `address` | Endereço completo (Rua, Número, Bairro, Cidade). |
| `bedrooms` | Quantidade de quartos. |
| `bathrooms` | Quantidade de banheiros. |
| `parking_spaces` | Quantidade de vagas de garagem. |
| `extract_date` | Data em que os dados foram coletados da plataforma. |
| `latitude` / `longitude` | Coordenadas geográficas para análise espacial e mapeamento. |

---

## 📁 Estrutura do Repositório
* `/dataset`: Contém o arquivo `SaoPaulo_OnlyAppartments_2024-11-25.csv`.
* `/docs`: Documentação do projeto e PDFs das etapas de entrega.

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem**: Python
* **Bibliotecas Principais**: a definir
* **Ambiente**: a definir