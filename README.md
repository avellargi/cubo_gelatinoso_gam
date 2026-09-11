<img src= "imagens/Cabecalho.png"/>

<h1 align="center">Análise de Desempenho de Algoritmo k-NN na Predição de Doença Renal Crônica</h1>

<p align="center">
  <img src="imagens/header (1).png" />
</p>

Esse repositório contém o código-fonte desenvolvido para a Entrega Parcial (denominada no sistema de gamificação 'Cubo Gelatinoso') da disciplina "Aprendizado de Máquina" do segundo semestre do Bacharelado em Ciência e Tecnologia da Ilum. O objetivo do trabalho é estudar o desempenho de um modelo induzido pelo algoritmo dos k-vizinhos mais próximos (k-NN) em um conjunto de dados que contém informações sobre Doença Renal Crônica (DRC). Para isso, são avaliadas diferentes configurações de hiperparâmetros, analisando seu impacto sobre a capacidade preditiva do modelo.

A DRC é uma condição caracterizada pela perda gradual e irreversível da função renal, sendo considerada um importante problema de saúde pública em escala mundial. Nesse contexto, técnicas de Aprendizado de Máquina podem auxiliar na identificação precoce de indivíduos com maior risco de desenvolver a doença, contribuindo para apoiar a tomada de decisão clínica, em um contexto em que a doença é subnotificada.

## Conjunto de Dados
O trabalho utiliza o conjunto de dados **Chronic Kidney Disease**, disponibilizado pelo UCI Machine Learning Repository. A base contém informações clínicas e laboratoriais de pacientes, incluindo atributos como idade, pressão arterial, glicemia, ureia, creatinina sérica, hemoglobina, sódio, potássio, presença de hipertensão, diabetes mellitus e anemia.
Após o pré-processamento dos dados, foram realizadas etapas de tratamento de valores faltantes, transformação de variáveis categóricas binárias e divisão dos dados em conjuntos de treinamento e teste utilizando a Estratégia de Holdout.

## Modelos Analisados
- **Modelo Baseline (DummyClassifier):** utilizado como referência para avaliar se os modelos desenvolvidos apresentam desempenho superior ao obtido por uma estratégia baseada na classe majoritária, isto é, na moda;
- **k-Nearest Neighbors (k-NN):** algoritmo supervisionado de classificação baseado na proximidade entre exemplos, em que a classe de uma observação é determinada a partir das classes de seus vizinhos mais próximos;
-  **Análise de Hiperparâmetros:** estudo do impacto de parâmetros como número de vizinhos k.
  
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

-Scikit-Learn (1.7.2): implementação dos modelos, divisão treino-teste e cálculo das métricas de desempenho.


## Acesso ao código
As informações detalhadas do projeto, incluindo a fundamentação teórica, as etapas de pré-processamento dos dados, a construção e treinamento dos modelos de aprendizado de máquina, a avaliação de desempenho e a análise dos resultados obtidos, estão disponíveis no repositório em: [código](https://github.com/avellargi/dinamica_populacional/tree/main/codigo)

## Autoria
| <img src="https://github.com/avellargi.png" width=115><br><sub>[Giovanna Avellar Machado](https://github.com/avellargi)</sub> |
| :--: |
Giovanna Avellar Machado - Aluna do Segundo Semestre do Bacharelado em Ciência, Tecnologia e Inovação da Ilum - Escola de Ciência 

## Professor Orientador
| <img loading="lazy" src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub> [Prof. Dr. Daneiel Roberto Cassar](http://lattes.cnpq.br/1717397276752482) | <img loading="lazy" src="https://github.com/user-attachments/assets/5be40392-5473-4b8b-b636-a55cbf0114fd" width=115><br>
| :--: | :---: | :---: |

## Referências Bibliográficas

- MATPLOTLIB DEVELOPMENT TEAM. *Matplotlib Pyplot tutorial*. Disponível em: <https://matplotlib.org/stable/tutorials/pyplot.html>. Acesso em: 10 ago. 2026.

- NUMPY DEVELOPERS. *NumPy documentation*. Disponível em: <https://numpy.org/doc/>. Acesso em: 10 ago. 2026.

- - RUBINI, L.; SOUNDARAPANDIAN, P.; ESWARAN, P. *Chronic Kidney Disease*. UCI Machine Learning Repository, 2015. Disponível em: <https://doi.org/10.24432/C5G020>. Acesso em: 17 ago. 2026.

- SCIPY. *scipy.integrate.odeint*. Disponível em: <https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.odeint.html>. Acesso em: 10 ago. 2026.

<img src= "imagens/Rodape.png"/>

