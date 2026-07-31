# knn_marketing

Este projeto foi desenvolvido como uma aplicação prática dos conhecimentos adquiridos no curso **“Clusterização: lidando com dados não rotulados”**, da Alura.

O objetivo foi utilizar técnicas de aprendizado de máquina não supervisionado para identificar grupos de usuários com interesses e comportamentos semelhantes, permitindo uma segmentação mais eficiente do público para campanhas de marketing.

## Objetivo do projeto

Neste projeto, foi aplicado o algoritmo de clusterização **K-means** para identificar agrupamentos de interesses entre usuários.

A partir da análise dos dados, buscamos segmentar o público em diferentes grupos, ou “bolhas de interesse”, considerando padrões de comportamento, preferências e características em comum.

Essa segmentação pode auxiliar empresas na criação de campanhas de marketing mais personalizadas, relevantes e assertivas, direcionando conteúdos e estratégias específicas para cada perfil de usuário.

## Problema de negócio

Campanhas de marketing genéricas nem sempre apresentam bons resultados, pois diferentes usuários possuem interesses, hábitos e necessidades distintos.

A clusterização permite descobrir padrões nos dados sem a necessidade de categorias previamente definidas. Dessa forma, usuários com características semelhantes podem ser agrupados, facilitando:

* a personalização de campanhas;
* a identificação de diferentes perfis de consumidores;
* a definição de estratégias específicas para cada grupo;
* o direcionamento mais eficiente de anúncios e conteúdos;
* a melhoria do relacionamento com o público.

## Metodologia

O projeto foi desenvolvido a partir das seguintes etapas:

1. Carregamento e exploração inicial dos dados;
2. Tratamento e preparação das variáveis;
3. Padronização dos dados;
4. Aplicação do algoritmo K-means;
5. Avaliação da quantidade adequada de clusters;
6. Análise das características de cada agrupamento;
7. Interpretação dos clusters no contexto de campanhas de marketing;
8. Desenvolvimento de uma aplicação interativa com Streamlit.

## Algoritmo utilizado

O **K-means** é um algoritmo de aprendizado de máquina não supervisionado utilizado para dividir observações em grupos.

O algoritmo busca formar clusters nos quais os elementos de um mesmo grupo sejam semelhantes entre si e diferentes dos elementos pertencentes aos demais grupos.

Como os dados utilizados não possuem rótulos previamente definidos, o K-means foi empregado para descobrir padrões e estruturas presentes no conjunto de dados.

## Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Streamlit
* Matplotlib e/ou Seaborn

## Como executar o projeto:

Acesse a aplicação publicada no Streamlit:

[🔗 Abrir aplicação](https://knnmarketing-kfvbschunskq6yohwyyzwk.streamlit.app/)

## Resultados esperados

A aplicação permite identificar a qual grupo de interesse um usuário provavelmente pertence, com base nas características informadas.

Os clusters encontrados podem representar diferentes perfis de público, possibilitando a criação de estratégias de marketing específicas para cada agrupamento.

É importante destacar que os nomes e interpretações dos clusters são definidos após a análise das características predominantes de cada grupo.

## Limitações

Este projeto possui finalidade educacional e foi desenvolvido a partir de um curso da Alura.

Os agrupamentos gerados dependem diretamente da qualidade, da quantidade e das características dos dados utilizados. Portanto, os resultados não devem ser interpretados como classificações absolutas dos usuários.

Em uma aplicação real, seria necessário utilizar uma base de dados mais ampla, validar periodicamente os clusters e avaliar o desempenho das campanhas direcionadas a cada grupo.

## Possíveis melhorias

Como próximas etapas, o projeto poderia ser expandido com:

* comparação do K-means com outros algoritmos de clusterização;
* redução de dimensionalidade com PCA;
* visualização interativa dos clusters;
* criação de nomes e personas para cada grupo;
* integração com uma base de dados real;
* acompanhamento dos resultados das campanhas;
* atualização periódica do modelo.

## Créditos

Projeto desenvolvido como prática do curso **“Clusterização: lidando com dados não rotulados”**, da Alura.


