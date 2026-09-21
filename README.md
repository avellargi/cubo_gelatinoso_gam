<img src= "imagens/cabeçalho"/>

<h1 align="center">Análise de Desempenho de Algoritmo k-NN na Predição de Doença Renal Crônica</h1>

<p align="center">
  <img src="imagens/headernova.png" />
</p>

Esse repositório contém o código-fonte desenvolvido para a Entrega Parcial (denominada no sistema de gamificação 'Cubo Gelatinoso') da disciplina "Aprendizado de Máquina" do segundo semestre do Bacharelado em Ciência e Tecnologia da Ilum. O objetivo do trabalho é estudar o desempenho de um modelo induzido pelo algoritmo dos k-vizinhos mais próximos (k-NN) em um conjunto de dados que contém informações sobre Doença Renal Crônica (DRC). Para isso, são avaliadas diferentes configurações de hiperparâmetros, analisando seu impacto sobre a capacidade preditiva do modelo.

A DRC é uma condição caracterizada pela perda gradual e irreversível da função renal, sendo considerada um importante problema de saúde pública em escala mundial. Nesse contexto, técnicas de Aprendizado de Máquina podem auxiliar na identificação precoce de indivíduos com maior risco de desenvolver a doença, contribuindo para apoiar a tomada de decisão clínica, em um contexto em que a doença é subnotificada.

## Conjunto de Dados
O trabalho utiliza o conjunto de dados **Chronic Kidney Disease**, disponibilizado pelo UCI Machine Learning Repository. A base contém informações clínicas e laboratoriais de pacientes, incluindo atributos como idade, pressão arterial, glicemia, ureia, creatinina sérica, hemoglobina, sódio, potássio, presença de hipertensão, diabetes mellitus e anemia.
Após o pré-processamento dos dados, foram realizadas etapas de tratamento de valores faltantes, transformação de variáveis categóricas binárias e divisão dos dados em conjuntos de treinamento e teste utilizando a Estratégia de Holdout.

## Modelos Analisados
- **Modelo Baseline (DummyClassifier):** utilizado como referência para avaliar se os modelos desenvolvidos apresentam desempenho superior ao obtido por uma estratégia baseada na classe majoritária, isto é, na moda;
- **k-Nearest Neighbors (k-NN):** algoritmo supervisionado de classificação baseado na proximidade entre exemplos, em que a classe de uma observação é determinada a partir das classes de seus vizinhos mais próximos;
-  **Análise de Hiperparâmetros:** estudo do impacto de parâmetros como número de vizinhos k (1 a 15), tipo de normalização linear adotada (StandardScaler, MinMaxScaler ou MaxAbsScaler) e distância (eEuclidiana, Manhattan ou Chebyshev). 
  
## Métricas de Desempenho
Os modelos foram analisados por meio das seguintes métricas:
- Acurácia;
- Precisão (Precision);
- Sensibilidade (Recall).

## Tecnologias Utilizadas
- Python (3.13.7): linguagem utilizada para o desenvolvimento do projeto;

- Pandas (2.3.3): utilizada para leitura, organização e manipulação de dados;

- NumPy (2.2.6): foi empregada para manipulação de arrays e operações matemáticas;

- Matplotlib (3.10.6): utilizada para a construção de gráficos e visualização dos resultados;

- Seaborn (0.13.2): foi empregada para a visualização estatística dos dados;

- Scikit-Learn (1.7.2): implementação dos modelos, divisão treino-teste e cálculo das métricas de desempenho.


## Acesso ao código
As informações detalhadas do projeto, incluindo a fundamentação teórica, as etapas de pré-processamento dos dados, a construção e treinamento dos modelos de aprendizado de máquina, a avaliação de desempenho e a análise dos resultados obtidos, estão disponíveis no repositório em: [código](https://github.com/avellargi/dinamica_populacional/tree/main/codigo)

## Autoria
| <img src="https://github.com/avellargi.png" width=115><br><sub>[Giovanna Avellar Machado](https://github.com/avellargi)</sub> |
| :--: |
Giovanna Avellar Machado - Aluna do Segundo Semestre do Bacharelado em Ciência, Tecnologia e Inovação da Ilum - Escola de Ciência 

## Professor Orientador
| <img src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub>[Prof. Dr. Daniel Roberto Cassar](http://lattes.cnpq.br/1717397276752482)</sub> |
| :--: |
Daniel Roberto Cassar - Docente Pesquisador da Ilum – Escola de Ciência. Doutorado em Ciência e Engenharia de Materiais (UFSCar) e Pós-Doutorado pela UFSCar. Atua na área de Informática de Materiais.

## Agradecimentos 

Agradeço aos estudantes da Ilum Glauber Nascimento de Oliveira e Gabriela Oliveira de Lima Cabral pelas trocas e discussões ao longo do desenvolvimento deste trabalho, que contribuiram para sua concretização.

## Referências Bibliográficas

- GBD 2023 CHRONIC KIDNEY DISEASE COLLABORATORS. Global, regional, and national burden of chronic kidney disease in adults, 1990–2023, and its attributable risk factors: a systematic analysis for the Global Burden of Disease Study 2023. The Lancet, v. 406, n. 10518, p. 2461-2482, 2025. DOI: 10.1016/S0140-6736(25)01853-7. Disponível em: https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(25)01853-7/fulltext. Acesso em: 10 ago. 2026.

- RUBINI, L.; SOUNDARAPANDIAN, P.; ESWARAN, P. Chronic Kidney Disease [Dataset]. UCI Machine Learning Repository, 2015. Disponível em: https://doi.org/10.24432/C5G020. Acesso em: 17 ago. 2026.

- MATPLOTLIB DEVELOPMENT TEAM. Matplotlib Pyplot tutorial. Disponível em: https://matplotlib.org/stable/tutorials/pyplot.html. Acesso em: 10 ago. 2026.

- NUMPY DEVELOPERS. NumPy documentation. Disponível em: https://numpy.org/doc/. Acesso em: 10 ago. 2026.

- PANDAS DEVELOPMENT TEAM. pandas documentation. Disponível em: https://pandas.pydata.org/docs/. Acesso em: 10 ago. 2026.

- SEABORN DEVELOPMENT TEAM. seaborn: statistical data visualization. Disponível em: https://seaborn.pydata.org/. Acesso em: 10 ago. 2026.

- SCIKIT-LEARN DEVELOPERS. scikit-learn: machine learning in Python. Disponível em: https://scikit-learn.org/stable/. Acesso em: 10 ago. 2026.

- HIDAYAT, Ramdhan. Understanding the Dummy Variable Trap. Medium, 29 jul. 2024. Disponível em: https://medium.com/@ramdhanhdy/understanding-the-dummy-variable-trap-78d00f8bf20a. Acesso em: 21 set. 2026.

- IBM. O que é redução da dimensionalidade?. IBM Think, 5 jan. 2024. Disponível em: https://www.ibm.com/br-pt/think/topics/dimensionality-reduction. Acesso em: 21 set. 2026.

- CASSAR, Daniel R. Divisão de dados em treino e teste. 2026. Jupyter Notebook. Material didático não publicado.

- CASSAR, Daniel R. Modelo linear e baseline. 2026. Jupyter Notebook. Material didático não publicado.

- CASSAR, Daniel R. Aprendizado de máquina, k-NN e métricas. 2026. Jupyter Notebook. Material didático não publicado.

- ANTHROPIC. Claude (Sonnet 5). São Francisco: Anthropic, 2026. Disponível em: https://claude.ai. Acesso em: 10 ago. 2026.

P.S. As referências estão ordenadas em ordem de aparição no documento.

<img src= "imagens/rodapé"/>
