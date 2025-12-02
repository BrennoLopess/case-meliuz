# 📊 Case Técnico de Data Analytics | Méliuz

## Visão Geral

Este repositório apresenta a solução completa desenvolvida para o processo seletivo de Estágio em Data Analytics da Méliuz. O material foi estruturado para demonstrar domínio técnico em análise de dados, comunicação clara, organização profissional e capacidade de transformar informações em insights acionáveis.

O projeto inclui análise exploratória, processamento dos dados, validação do teste A/B/C, visualizações e uma conclusão executiva alinhada ao contexto de negócios. Toda a análise foi desenvolvida em Python utilizando Jupyter Notebook.

---

## 🎯 Objetivo do Projeto

A base de dados fornecida contém quatro arquivos principais:

- **clientes.csv**
- **pedidos.csv**
- **itens_pedido.csv**
- **produtos.csv**

O objetivo geral do estudo é:

- Analisar o comportamento de compra dos clientes.
- Avaliar o desempenho dos grupos do teste A/B/C.
- Identificar padrões geográficos de vendas.
- Investigar possíveis relações entre características do pedido e seu status.
- Gerar visualizações que facilitem a interpretação dos resultados.
- Produzir uma conclusão final sólida e orientada ao negócio.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- pandasql
- Jupyter Notebook

---

## 📁 Estrutura do Repositório

```
case-meliuz/
│── meliuz_abc_teste.ipynb      # Notebook completo da análise
│── clientes.csv
│── pedidos.csv
│── produtos.csv
│── itens_pedido.csv
│── README.txt
```

---

## 📊 Principais Análises Realizadas

### 1. Desempenho dos Grupos A, B e C

Foram avaliadas as seguintes métricas:

- Quantidade de clientes por grupo
- Quantidade de pedidos
- Taxa de conversão
- Ticket médio
- Receita total
- ARPU (Receita Média por Cliente)
- Distribuição de status

📌 **Conclusão:**  
O **Grupo B** apresentou desempenho superior em todas as métricas. Mesmo com número similar de clientes, obteve:

- Maior receita total  
- Maior ticket médio  
- Maior ARPU  

Isso indica que o comportamento induzido pela variante do Grupo B é o mais favorável.  
**Recomendação:** Adotar o Grupo B como funcionalidade oficial.

---

### 2. Influência do Estado nas Vendas

A análise geográfica demonstrou diferenças significativas entre os estados:

- Estados com maior receita: RR, MG, MA, AL e GO.
- Estados com menor desempenho: RS, RN e PB.

📌 **Conclusão:**  
Há impacto direto do estado no comportamento de compra dos clientes.

---

### 3. Ranking de Estados e Cidades

Após consolidar a análise:

- **São Paulo** aparece como a cidade com maior receita, considerando variações de grafia presentes nos dados.
- Outros polos relevantes: Curitiba, Belo Horizonte, Goiânia e Rio de Janeiro.

📌 **Conclusão:**  
O desempenho é fortemente concentrado em centros urbanos de alto fluxo.

---

### 4. Categoria e Quantidade de Itens x Status do Pedido

Foram avaliadas:

- Taxas de confirmação
- Cancelamentos
- Pendências por categoria
- Comportamento por faixas de quantidade de itens

📌 **Conclusão:**  
Não há diferença significativa entre categorias ou quantidade de itens.  
O status do pedido é estável e consistente entre diversas combinações de produtos e quantidades.

---

### 5. Métricas Adicionais Construídas

Para elevar o nível do case, foram incluídas análises complementares:

- **Distribuição geral dos status**  
- **Ticket médio mensal**  
- **Top 10 produtos mais vendidos**

📌 **Conclusão:**  
O sistema é estável, o ticket médio não apresenta sazonalidade acentuada e o portfólio é bem distribuído.

---

## 📈 Visualizações Criadas

- Gráfico da distribuição dos status dos pedidos  
- Evolução mensal do ticket médio  
- Barras horizontais de estados com maior receita  
- Barras horizontais de cidades com maior receita  
- Top 10 produtos mais vendidos  

As visualizações reforçam e complementam os resultados estatísticos.

---

## 🧠 Conclusão Executiva

A análise indica:

- O **Grupo B** deve ser priorizado para a funcionalidade final.
- O comportamento de compra é influenciado pela localização geográfica.
- A operação é estável, com predominância de pedidos confirmados.
- A categoria e quantidade de itens não influenciam o status final.
- O portfólio apresenta boa diversificação e distribuição equilibrada.

O estudo cumpre completamente o escopo proposto no case e oferece uma visão clara, estratégica e fundamentada.

---

## 👤 Autor

**Brenno Lopes**  
Estudante de Engenharia de Software  
Foco em Dados e Inteligência Artificial  
GitHub: github.com/BrennoLopess
