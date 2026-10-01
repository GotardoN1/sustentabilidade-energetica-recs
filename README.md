<div align="center">

<a href="https://gotardon1.github.io/GotardoN1/#projeto/recs">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GotardoN1/GotardoN1/main/assets/projetos/recs-dark.svg">
    <img src="https://raw.githubusercontent.com/GotardoN1/GotardoN1/main/assets/projetos/recs-light.svg" width="100%" alt="Sustentabilidade energética e RECs">
  </picture>
</a>

<img src="https://img.shields.io/badge/Python-pandas_·_NumPy-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=161b22" alt="Python">
<img src="https://img.shields.io/badge/MySQL-Data_Warehouse-4479A1?style=flat-square&logo=mysql&logoColor=white&labelColor=161b22" alt="MySQL">
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black&labelColor=161b22" alt="Power BI">
<img src="https://img.shields.io/badge/tema-energia_renov%C3%A1vel-2dd4bf?style=flat-square&labelColor=161b22" alt="Energia renovável">

**[Ver no portfólio interativo](https://gotardon1.github.io/GotardoN1/#projeto/recs)** · **[Perfil](https://github.com/GotardoN1)**

</div>

## Sobre

Análise do consumo de energia e da adoção de **Certificados de Energia Renovável (RECs)** por empresas. O projeto usa engenharia de dados e business intelligence para apoiar decisões sustentáveis.

O pano de fundo é a transição energética: trocar combustíveis fósseis por fontes alternativas. Com dados regionais, com foco em **Salvador**, e modelagem dimensional, o projeto aponta oportunidades de compra de RECs. Isso ajuda as empresas a cumprir metas de emissão de **gases de efeito estufa (GEE)**.

## Arquitetura da solução

```mermaid
flowchart LR
    A[🔌 Ingestão<br>fontes de energia e<br>consumo regional] --> B[🐍 Tratamento<br>Python · pandas · NumPy]
    B --> C[(🗄️ Data warehouse<br>MySQL · esquema estrela)]
    C --> D[📊 Power BI<br>impacto e viabilidade]
    D --> E{Comprar RECs?}
```

| Etapa | O que acontece |
|---|---|
| **1. Ingestão** | Coleta de dados sobre fontes de energia e consumo regional |
| **2. Tratamento** | Limpeza e filtragem com Python (pandas e NumPy) |
| **3. Armazenamento** | Data warehouse em MySQL para consultas analíticas |
| **4. Visualização** | Painel no Power BI com indicadores de impacto e viabilidade |

**Conceitos aplicados:** ETL, modelagem dimensional (esquema estrela) e sustentabilidade corporativa.

## Neste repositório

| Arquivo | Conteúdo |
|---|---|
| [`Apresentacao2.pptx`](Apresentacao2.pptx) | Apresentação do projeto, com a arquitetura e os resultados |

## Autores

| | |
|---|---|
| **Fabrício Corrêa de Souza** | **Matheus Gonçalves Gotardo** |
| **Nicole Guerreiro Diniz** | **Willian de Andrade Baggio** |

---

<div align="center">
<sub>Mais projetos: <a href="https://github.com/GotardoN1/bi-eficiencia-energetica">BI e eficiência energética</a> · <a href="https://github.com/GotardoN1/grafo-social">Grafo Social</a> · <a href="https://gotardon1.github.io/GotardoN1/#projetos">todos no portfólio</a></sub>
</div>
