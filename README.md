# Cyber Coffee — Pesquisa de Mercado para Abertura de Cafeteria em Los Angeles

## Descrição do Projeto
Projeto de análise de dados aplicado ao mercado de restaurantes de Los Angeles. O contexto do projeto é a abertura de uma cafeteria com garçons robôs — um negócio promissor, mas de alto investimento. O objetivo foi realizar uma pesquisa de mercado com dados de código aberto sobre estabelecimentos em LA, a fim de apresentar aos investidores um panorama do mercado atual e avaliar a viabilidade do negócio mesmo quando o diferencial dos robôs deixar de ser novidade.

---

## Metodologia
1. **Pré-processamento dos dados**
   - Remoção de valores ausentes, reset de índice e conversão das colunas `chain` e `object_type` para o tipo categórico.
2. **Análise Exploratória de Dados (EDA)**
   - Distribuição dos tipos de estabelecimentos, proporção de redes vs. independentes, capacidade média por tipo, análise geográfica por ruas e distribuição de assentos nas ruas mais populares.
3. **Interpretação e recomendações**
   - Identificação do perfil ideal de estabelecimento para abertura de uma rede, com recomendação fundamentada nos dados.

---

## Principais insights

- **Restaurantes dominam o mercado**, representando cerca de 75% dos estabelecimentos, seguidos por fast-foods (11%) e cafés (4%).

- **Cafés e fast-foods têm maior taxa de operação em rede:** 61% dos cafés e 56% dos fast-foods funcionam em formato de rede, enquanto apenas 31% dos restaurantes operam assim.

- **Capacidade média por tipo:** restaurantes possuem em média 48 assentos, fast-foods 31 e cafés 25 — estrutura mais enxuta e replicável.

- **25% das ruas com estabelecimentos possuem apenas um estabelecimento**, indicando grande dispersão geográfica e potencial de expansão em locais pouco explorados.

- **Conclusão geral:** Cafés são a melhor aposta para quem deseja investir em uma rede. Têm baixa presença em número absoluto, mas alta taxa de replicação no modelo de rede, estrutura enxuta e demanda consistente. A recomendação é abrir um café com cerca de 25 assentos, aproveitando o diferencial dos garçons robôs como fator de escalabilidade frente a outras redes de café.

---

## 📊 Apresentação dos Resultados

Além do notebook com toda a análise, este projeto conta com material de apresentação voltado à comunicação dos resultados para públicos não técnicos.

### 📄 Apresentação em PowerPoint
Foi elaborada uma apresentação no PowerPoint com o resumo do projeto, principais análises e recomendação final para os investidores.

➡️ **Acesse a apresentação:**  
[Apresentação — Cafeteria com Garçons Robô: Análise de Viabilidade (PowerPoint)](https://1drv.ms/p/c/740f96b86bb24e1a/EXeFm5CUy-tHkJ5Yp0oUyGwBuefBSVQxk99vEzDXDgobag?e=gF9eHr)

> *A apresentação sintetiza os principais insights de forma objetiva, com foco em impacto para o negócio e apoio à tomada de decisão dos investidores.*

---

## 📂 Conteúdo do Repositório

- **Notebook (.ipynb):** análise completa, incluindo pré-processamento, EDA e conclusões
- **README (.md):** este arquivo

---

## Tecnologias e bibliotecas
- Linguagem: **Python**
- Bibliotecas: **pandas**, **matplotlib**, **seaborn**, **plotly**
- Notebook: **Jupyter Notebook**
- Apresentação: **Microsoft PowerPoint**

---

## Contato

Willian De Souza Pereira — ws13292@gmail.com

LinkedIn: https://linkedin.com/in/willian-de-souza-pereira-b69109202

## Licença

Este repositório está disponível para estudo e demonstração. Sinta-se à vontade para clonar, adaptar e abrir *issues* com dúvidas ou sugestões.
