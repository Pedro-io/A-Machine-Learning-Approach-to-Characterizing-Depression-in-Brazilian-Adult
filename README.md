Utilizando Modelos de Machine Learning para a Caracterização da Depressão em Adultos no Brasil

### Descrição do Projeto

Este projeto utiliza técnicas de aprendizado de máquina para caracterizar o perfil de indivíduos adultos com depressão no Brasil, a partir da Pesquisa Nacional de Saúde (PNS) de 2019. O objetivo principal é desenvolver e avaliar modelos preditivos de depressão, empregando algoritmos de Árvore de Decisão, Naive Bayes e Random Forest.

### Objetivo

* Identificar fatores de risco associados à depressão em adultos no Brasil.
* Desenvolver e avaliar modelos de Machine Learning para a predição de depressão.
* Contribuir para a compreensão da depressão e a elaboração de estratégias de prevenção e tratamento mais eficazes.

### Tecnologias Utilizadas

* Linguagem de Programação: Python
* Bibliotecas:
    * Scikit-learn (para Machine Learning)
    * Pandas (para manipulação de dados)
    * Matplotlib (para visualização de dados)
    * Seaborn (para visualização de dados)
    * Imbalanced-learn (para balanceamento de dados)
* Base de Dados: Pesquisa Nacional de Saúde (PNS) 2019

### Metodologia

A metodologia utilizada envolveu as seguintes etapas:

1. **Entendimento do Domínio e Seleção Conceitual de Atributos:** Utilizando o Método CAPTO, foi construído um modelo conceitual que integra diferentes dimensões da depressão.
2. **Preparação do Conjunto de Dados:**
    * Combinação de atributos relacionados à saúde física, renda, trabalho, doenças crônicas, saneamento e alimentação.
    * Tratamento de valores ausentes.
    * Tratamento de outliers.
    * Remoção de atributos irrelevantes.
    * Codificação dos dados.
    * Divisão da base de dados em conjuntos de treinamento e teste.
    * Balanceamento da base de dados.
3. **Mineração de Dados:**
    * Treinamento de modelos de Machine Learning: Árvore de Decisão, Naive Bayes e Random Forest.
    * Otimização de hiperparâmetros utilizando RandomizedSearchCV.
    * Validação-cruzada de 10 dobras.
4. **Avaliação do Desempenho:**
    * Utilização de métricas de classificação: Precisão, Revocação, F1-score, Curva ROC e AUC.

### Resultados

* Os modelos apresentaram desempenho satisfatório na detecção de casos de depressão, com taxas de verdadeiros positivos (TP) significativas.
* A Floresta Aleatória se destacou como o modelo com melhor desempenho geral, atingindo uma taxa de TP de 92,66%.
* A análise das regras da Árvore de Decisão revelou a importância de fatores como problemas de sono, consumo alimentar, doenças crônicas e rede social como indicadores de risco para a depressão.

### Conclusões e Trabalhos Futuros

* Os resultados corroboram a necessidade de considerar fatores socioeconômicos, estilo de vida e condições de saúde física na prevenção e tratamento da depressão.
* O estudo destaca o potencial do aprendizado de máquina para a identificação de fatores de risco e o desenvolvimento de estratégias de intervenção mais eficazes.
* Para trabalhos futuros, pretende-se investigar técnicas mais avançadas de balanceamento de dados e a inclusão de atributos adicionais relacionadas à saúde mental.

### Como Executar o Projeto

1. **Clone o repositório:** `git clone https://github.com/seu-usuario/depressao-machine-learning.git`
2. **Crie um ambiente virtual:** `python3 -m venv env`
3. **Ative o ambiente virtual:** `source env/bin/activate`
4. **Instale as dependências:** `pip install -r requirements.txt`
5. **Execute o script:** `python main.py`

### Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, enviar pull requests ou entrar em contato comigo para discutir ideias.

### Referências

[1] Ministério da Saúde (2020). Saúde Mental no Brasil: Panorama 2020.
[2] Zarate, L. E. G. (2023). CAPTO - Um Método para Captura e Transformação de Conhecimento Tácito em Conhecimento Explícito.
[3] Zulfiqar, A., Ahmed, M. U., Ahmad, M., Khan, M. A., & Lee, I. (2020). Predicting depression severity using social media posts based on deep learning and transfer learning techniques. Computers in Human Behavior, 107, 106294.
[4] Losada-Barrios, D. C., Valencia, V. R., & López-Cobo, P. (2021). Machine learning for the detection and prediction of depression in university students. Journal of Technology in Human Services, 39(1), 1-26.
[5] Acharya, U. R., Sree, S. K., Chatterjee, M., & Janakiraman, N. (2022). Explainable machine learning models for predicting depression severity using ECG signals. IEEE Access, 10, 40548-40561.
[6] Li, J., Li, X., Li, M., Zhou, D., & Huang, M. (2023). Smartphone-based passive data for predicting changes in depression severity in young adults: A machine learning approach. Behaviour Research and Therapy, 166, 104225.
[7] Batista, J. L., Sousa, M. C. S., & Almeida, A. T. (2022). Fatores associados à depressão em adultos no Brasil: Uma análise da Pesquisa Nacional de Saúde (PNS) 2019. Revista Brasileira de Saúde Materno-Infantil, 22(2), 365-375.
[8] Luppino, F., de Wit, L. M., & van Lenthe, F. (2010). Overweight and obesity in relation to depression: A systematic review and meta-analysis. The American Journal of Clinical Nutrition, 91(5), 1379-1386.
[9] Lorant, V.,  &  Blanche,  F.  (2003).  Socioeconomic  position  and  depressive  symptoms  in  France.  Journal  of  Epidemiology  and  Community  Health, 57(5), 357-361.
[10] Stansfeld, S. A.,  &  Marmot,  M. G.  (2006).  Psychosocial  work  environment  and  risk  of  coronary  heart  disease:  a  systematic  review  and  meta-analysis.  Journal  of  Epidemiology  and  Community  Health, 60(1), 1-9.
[11] Virtanen, M.,  &  Kivimaki,  M. (2018). Overtime  work  and  risk  of  depression  and  anxiety  disorders:  a  systematic  review  and  meta-analysis.  Occupational  and  Environmental  Medicine, 75(3), 178-186.
[12] Kessler, R. C.,  &  Barker,  W.  C.  (1995).  Childhood  adversity  and  adult  psychiatric  disorders:  a  review  and  implications  for  prevention.  International  Review  of  Psychiatry, 7(1-2), 69-88.
[13] Beck,  A.  T.  (1979).  Cognitive  therapy  and  the  emotional  disorders.  International  Universities  Press.
[14] Kendler,  K. S.,  &  Prescott,  C. A.  (2006).  The  Swedish  twin  study  of  anxiety  disorders:  a  review  of  the  findings  over  25  years.  Journal  of  Psychiatric  Research, 40(8), 551-563.
[15] Smith,  K. D.,  &  Glass,  T. A.  (2006).  Factors  associated  with  depression  in  women  with  chronic  pain.  Pain  Medicine, 7(6), 429-437.
[16] Beck,  A. T.,  &  Ward,  C. H.  (1961).  An  inventory  for  measuring  depression.  Journal  of  Consulting  Psychology, 25(6), 561-571.
[17] Kuehner,  C.  (2017).  Gender  differences  in  depression.  Current  Opinion  in  Psychiatry, 30(4), 293-298.
[18] Fiske,  A.  (2009).  Depression.  Oxford  University  Press.
[19] Barbosa, M. T.,  &  Machado,  C. M. (2020). Terapia nutricional: uma ferramenta fundamental para o bem-estar mental. Revista Brasileira de Nutrição, 33(1), 1-12.
[20] Lai,  J. Y.,  &  Wolk,  A.  (2015).  Prevalence  of  depression  and  anxiety  disorders  among  adults  with  metabolic  syndrome  in  the  United  States:  an  analysis  of  NHANES  2005-2010.  Journal  of  Clinical  Lipidology, 9(1), 24-33.
[21] Skogen,  J. C.,  &  Heier,  L.  (2014).  Anxiety  and  depression  in  relation  to  diet  quality  among  young  adults  in  Norway:  the  Nord-Trøndelag  Health  Study  (HUNT).  Public  Health  Nutrition, 17(9), 1931-1939.
[22] Dondena, P.,  &  D'Addio,  A.  (2017).  Predicting  customer  churn  with  machine  learning:  a  comparison  of  different  methods.  In  Proceedings  of  the  2017  International  Conference  on  Machine  Learning  and  Data  Mining  (MLDM)  (pp.  38-45).
[23] Witten,  I. H.,  &  Frank,  E. (2016).  Data  mining:  practical  machine  learning  tools  and  techniques.  Morgan  Kaufmann.
[24] Liu,  B.,  &  Wang,  L.  (2022).  Machine  learning  for  predicting  depression:  a  comprehensive  survey.  IEEE  Access, 10, 116776-116804.
[25] Loyola,  P. F.,  &  Nunes,  B. L.  (2019).  Aprendizado  de  máquina  na  detecção  de  depressão:  uma  revisão  sistemática.  Revista  Brasileira  de  Informática  em  Saúde, 19(1), 1-16.


