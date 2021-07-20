# DS_RoadMap

## 1. Definições Preliminares
Este é um repositório de código para os principais conhecimentos concernentes à área de ciência de dados. O seu conteúdo é baseado em duas principais referências:

1. "Data Scientist Roadmap", de [Swami Chandrasekaran](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/).
2. Repositório para o *roadmap* anterior, de [MrMimic](https://github.com/MrMimic/data-scientist-roadmap).

O *roadmap* em questão mostra os conhecimentos que um aspirante a cientista de dados deve desenvolver ao longo do tempo, como um guia de linhas de trem, vide figura abaixo:

![](https://camo.githubusercontent.com/b6482a1fcf61b0f1b479c9f129b00e09ffb100026db15502b351b083f4f5fd3f/687474703a2f2f6e6972766163616e612e636f6d2f74686f75676874732f77702d636f6e74656e742f75706c6f6164732f323031332f30372f526f6164546f44617461536369656e74697374312e706e67)

São 10 linhas de trem (seções) e mais de 200 estações (tópicos de conhecimento):

- Linha 1-roxa: Fundamentos;
- Linha 2-azul: Estatística;
- Linha 3-verde: Programação;
- Linha 4-oliva: Aprendizado de máquina;
- Linha 5-laranja: Mineração de textos e Processamento de Língua Natural (PLN);
- Linha 6-vermelha: Visualização de dados;
- Linha 7-rosa: *Big Data*;
- Linha 8-esmeralda: Ingestão de dados;
- Linha 9-lilás:  *Munging* de dados;
- Linha 10-marrom: Caixa de ferramentas.

Considere este repositório como uma referência em português para o assunto. Não é intuito dos autores, portanto, impor uma ordem direta e fixa de estudos/domínio de conhecimento.

Cada seção do índice ("linha de trem" do mapa) mostrada a seguir estará *linkada* às pastas do diretório à medida que novos conteúdos forem adicionados. Cada pasta possui uma explicação de cada "linha de trem" da imagem original e código. Por exemplo, a seção 1 (linha 1-roxa), tem todo o seu conteúdo explicado na pasta "01_Fundamentos", bem como código para cada tópico (estação de trem) de Fundamentos.

## 2. Observações

- Repare que existe uma "baldeação" entre as linhas 2-azul e 3-verde. O aprendizado de análise exploratória de dados (na linha azul) pode ser obtido juntamente com o de programação (linha verde).

- A linha 4-oliva se conecta à linha 5-laranja, compreendendo 50% do conhecimento do cientista de dados. Note que a linha 5 é um aprofundamento/especialização de uma área maior. Ou seja, mineração de textos e processamento de língua natural estão compreendidas na área aprendizado de máquina.

- Note que a linha 6-vermelha não está conectada à nenhuma outra linha. Trata-se do conhecimento de visualização de dados, necessário para apresentar informações importantes durante o trabalho do cientista de dados. (Há casos em que a responsabilidade da visualização dos dados fica a cargo do analista de dados.) Note, também, que a visualização corresponde a 40% do conhecimento de um cientista de dados.

- A linha-7 rosa também está representada de maneira independente. Note, neste caso, que *big data* é uma área muito grande que até mesmo extrapola o conhecimento necessário para um cientista de dados. Por exemplo, engenheiros de dados realizam *ETL* (extração, transformação e carregamento) sobre dados do universo *big data*. Dessa forma, veja que, ao concluir esta etapa, o aspirante a cientista de dados obtém estimados 60% do conhecimento necessário. *Nota deste autor: obtenha o conhecimento básico sobre as estações dessa linha. Cada estação corresponde a assuntos muito vastos que escapam do conhecimento de um cientista de dados, atingindo o espectro do conhecimento de um engenheiro de dados.*

- As linhas 8-esmeralda e 9-lilás possuem uma baldeação entre si. Ambas as linhas se referem a processos importantes relacionados à manipulação de dados.

## 3. Compartilhamento do Repositório

Sinta-se à vontade para baixar o conteúdo deste rep. e/ou contribuir com este projeto de alguma forma. Toda interação que pudermos fazer será bem-vinda! 🙂

**--->Texto longo abaixo<---**

## Índice

1. [Fundamentos (5% do conhecimento de um cientista de dados)](https://github.com/Andygrammer/DS_RoadMap/tree/main/01_Fundamentos)
    1. Fundamentos sobre matrizes e álgebra linear
    2. Funções hash, árvore binária, O(n)
    3. Álgebra relacional, banco de dados básico
    4. Joins inner, outer, cross e theta
    5. Teorema CAP
    6. Tabulação de dados
    7. Entropia
    8. Data Frames e Séries
    9. Fragmentação
    10. OLAP
    11. Modelos de dados multidimensionais
    12. *ETL* (extração, transformação e carregamento)
    13. Relatórios vs. BI vs. Analytics
    14. JSON e XML
    15. NoSQL
    16. Regex
    17. Vendor Landscape
    18. Instalação/configuração de ambiente
2. Estatística (30%)
    1. Escolhendo um dataset (conjunto de dados) via repositório UCI
    2. Estatística descritiva (média, mediana, amplitude, desvio padrão e variância)
    3. Análise Exploratória de Dados (AED)
    4. Histogramas
    5. Percentis e pontos fora da curva (*outliers*)
    6. Teoria da probabilidade
    7. Teorema Bayes
    8. Variáveis aleatórias
    9. Função Fistribuição Acumulada (FDA)
    10. Distribuições contínuas (Normal, Poisson, Gaussiana)
    11. Distorção
    12. ANOVA
    13. Função Densidade de Probabilidade (FDP)
    14. Teorema central do limite
    15. Método de Monte Carlo
    16. Teste de hipóteses
    17. Valor-p
    18. Teste do qui-quadrado
    19. Estimador
    20. Intervalo de confiança
    21. Máxima verossimilhança (*maximum-likelihood*, ou *MLE*)
    22. Estimativa de Densidade Kernel (EDK)
    23. Regressão
    24. Covariância
    25. Correlação
    26. Coeficiente de correlação de Pearson
    27. Causalidade
    28. Método dos Mínimos Quadrados (MMQ)
    29. Distância Euclidiana
3. Programação (15%)
    1. Instalação de pacotes
    2. Análise fatorial
    3. Funções
    4. Manipulação de Data Frames
    5. Subconjuntos de dados
    6. Leitura de dados brutos (*raw data*)
    7. Leitura de dados no formato *CSV*
    8. Data Frames
    9. Listas
    10. Fatores
    11. Arrays
    12. Matrizes
    13. Vetores
    14. Sistema RapidMiner
    15. Variáveis
    16. Sistema IBM SPSS
    17. Expressões
    18. Linguagem R básica
    19. Instalação do R/R Studio
    20. Trabalhando com Excel
    21. Linguagem Python básica
4. Aprendizado de Máquina (50%)
    1. O que é aprendizado de máquina
    2. Variáveis numéricas
    3. Variáveis categóricas
    4. Aprendizado supervisionado
    5. Aprendizado não-supervisionado
    6. Conceitos, entradas (*inputs*) e atributos
    7. Dados de treinamento e teste
    8. Classificador
    9. Predição
    10. Lift
    11. Sobreajuste (*overfitting*)
    12. Viés e variância
    13. Árvores e classificação
    14. Taxa de classificação
    15. Árvores de decisão
    16. Boosting
    17. Classificadores Naive Bayes
    18. K-vizinhos mais próximos (*KNN*)
    19. Regressão logística
    20. Regressão com ranking
    21. Regressão linear
    22. Regressão com Perceptron
    23. Clustering hierárquico
    24. Clustering com K-means
    25. Redes Neurais Aritificiais
    26. Análise de sentimento
    27. Filtragem colaborativa
    28. Tagging
5. Mineração de textos / Processamento de Língua Natural (PLN) (50%)
    1. Mapeamento de vocabulário
    2. Classificação de textos
    3. Usando o NLTK (*Natural Language Toolkit*)
    4. Usando o Weka
    5. Usando o Apache Mahout
    6. Extração de características (*features*)
    7. Análise de marketing
    8. Regras de associação
    9. Máquinas de Vetores de Suporte (MVS, ou *SVM*)
    10. Frequência de termos e peso
    11. Matriz de documentos e termos
    12. *UIMA* (arquitetura para gerenciamento de informações não estruturadas)
    13. Análise de textos
    14. Reconhecimento de Entidades Nomeadas (REN, ou *NER*)
    15. Córpus
6. Visualização (40%)
    1. Exploração de dados em R (histograma, diagrama de caixa, etc.)
    2. Visualização *uni*, *bi* e multivariada de dados
    3. Pacote ggplot2
    4. Histograma e gráfico de pizza (visualização *univariada*)
    5. Árvore e mapa de árvore
    6. Gráfico de dispersão (vis. *bivariada*)
    7. Gráfico de linhas (vis. *bivariada*)
    8. Gráficos espaciais
    9. Gráficos de pesquisa
    10. Linha do tempo
    11. Árvore de decisão
    12. Biblioteca D3.js
    13. Ferramenta InfoVis
    14. Ferramenta IBM Many Eyes
    15. Ferramenta Tableau
7. *Big Data* (60%)
    1. MongoDB, Neo4j
    2. Banco de dados Cassandra
    3. Pacote rmr
    4. Rhadoop, RHIPE
    5. Storm: Hadoop em tempo real
    6. Zookeeper, Avro
    7. Usando o Mahout
    8. Scribe, Chukwa para Weblog
    9. DWH com Hive
    10. SQL com Pig
    11. Flume, Scribe para dados não-estruturados
    12. Sqoop: carregando dados no HDFS
    13. Programação MIR
    14. Rastreamento de trabalho e tarefa (*job and task tracker*)
    15. Nodos de nome e dados
    16. Instalação/configuração do Hadoop (IBM/Cloudera/HortonWorks)
    17. Princípios de replicação de dados
    18. HDFS (Sistema de Arquivos Distribuído do Hadoop)
    19. Componentes do Hadoop
    20. Fundamentos de MapReduce
8. Ingestão de dados (80%)
    1. Resumo sobre formatos de dados
    2. Descoberta de dados
    3. 




