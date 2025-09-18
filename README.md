# Estudo de Análise de Redes Sociais: Círculos de Amizade do Facebook

## 📝 Descrição
Este repositório é um projeto de estudo focado em aplicar e solidificar conceitos fundamentais de Análise de Rede Social (SNA). Utilizando o dataset "Social circles: Facebook" do SNAP, o projeto explora a estrutura de uma rede de amizades para identificar "círculos sociais" (comunidades) e analisar as propriedades topológicas do grafo.

O objetivo principal é servir como um guia prático e didático, onde cada etapa da análise é comentada para reforçar o conhecimento teórico.

## 🧠 Conceitos de Análise de Redes Abordados
Este estudo prático aborda os seguintes conceitos teóricos:
* **Criação de Grafos:** Carregamento de uma rede a partir de uma lista de arestas.
* **Propriedades Globais da Rede:**
    * **Densidade:** Quão conectada a rede é como um todo.
    * **Diâmetro:** A maior "distância" entre dois nós na rede.
    * **Coeficiente de Clusterização e Transitividade:** A tendência dos nós de formarem "panelinhas" (triângulos).
* **Métricas de Centralidade:**
    * **Centralidade de Grau (Degree):** A popularidade de um nó.
    * **Centralidade de Intermediação (Betweenness):** A importância de um nó como "ponte" no fluxo de informação.
    * **Centralidade de Proximidade (Closeness):** A capacidade de um nó de alcançar outros rapidamente.
* **Detecção de Comunidades:** Aplicação de algoritmos (ex: Louvain) para encontrar grupos densamente conectados.
* **Avaliação de Algoritmos:** Comparação das comunidades detectadas com um "ground truth" para validar os resultados.

## 📊 Dataset
O dataset utilizado é o **"Social circles: Facebook"**, do repositório SNAP (Stanford Network Analysis Project).

* **Fonte:** [SNAP - Facebook Social Circles](https://snap.stanford.edu/data/ego-Facebook.html)
* **Citação:** J. McAuley and J. Leskovec. Learning to Discover Social Circles in Ego Networks. NIPS, 2012.
