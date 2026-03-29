# 📊 Relatório Power BI — Página 3: Visuals Geográficos e por Segmento

## Descrição

A terceira página do relatório é dedicada à **análise visual de dados geográficos e por segmento de mercado**. O objetivo é desenvolver familiaridade com a criação de visuais no Power BI, especialmente mapas e gráficos de pizza. Layouts mais elaborados serão abordados em módulos avançados.

---

## Visuais da Página

### 🗺️ Mapa 1 — Vendas e Unidades por País

| Propriedade     | Configuração                        |
|-----------------|-------------------------------------|
| Tipo de visual  | Mapa (Map)                          |
| Localização     | Campo `Country` (País)              |
| Tamanho bolha   | Soma de `Sales` (Vendas)            |
| Legenda / Info  | Soma de `Units Sold` (Unidades Vendidas) |

**Objetivo:** Visualizar geograficamente o volume de vendas e a quantidade de unidades vendidas por país.

---

### 🗺️ Mapa 2 — Lucro por País

| Propriedade     | Configuração                        |
|-----------------|-------------------------------------|
| Tipo de visual  | Mapa (Map)                          |
| Localização     | Campo `Country` (País)              |
| Tamanho bolha   | Soma de `Profit` (Lucro)            |

**Objetivo:** Identificar quais países geram maior lucro, permitindo análise de performance geográfica.

---

### 🥧 Pizza — Lucro por Segmento

| Propriedade     | Configuração                        |
|-----------------|-------------------------------------|
| Tipo de visual  | Gráfico de Pizza (Pie Chart)        |
| Legenda         | Campo `Segment` (Segmento)          |
| Valores         | Soma de `Profit` (Lucro)            |

**Objetivo:** Comparar a participação de cada segmento de mercado no lucro total.

---

## Campos Utilizados

| Campo           | Descrição                              |
|-----------------|----------------------------------------|
| `Country`       | País de origem da venda                |
| `Sales`         | Valor total de vendas                  |
| `Units Sold`    | Quantidade de unidades vendidas        |
| `Profit`        | Lucro gerado                           |
| `Segment`       | Segmento de mercado (ex: Government, Midmarket, etc.) |

---

## Objetivo de Aprendizado

> Esta página visa treinar a **criação e configuração de visuais** no Power BI, com foco em:
> - Mapas geográficos com métricas de tamanho e cor
> - Gráficos de pizza para distribuição por categoria
> - Uso de campos de localização para geocodificação automática

---

## Observações

- Certifique-se de que o campo `Country` esteja categorizado como **"País/Região"** nas configurações de coluna para que o mapa funcione corretamente.
- Para o gráfico de pizza, habilite os **rótulos de dados** para exibir percentual por segmento.
- O layout detalhado da página será refinado em módulos mais avançados do curso.
