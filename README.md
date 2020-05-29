# [Previsão de Séries Temporais do Preço do Boi Gordo CEPEA/B3](https://nbviewer.jupyter.org/github/bobcastaldeli/Prediction-Cattle-Price-CEPEA-B3/blob/master/Cattle-Time-Series.ipynb)

Para realizar as estimativas de preços e demanda, até mesmo, compreeder o mercado de modo geral,
frequentemente os gestores levam em consideração conhecimentos técnicos e práticos adquiridos no
dia a dia do negócio. No entanto, com o grande volume de dados que as empresas estão gerando
nos últimos anos, a gestão de riscos e a identificação das tendencias de mercado se tornaram mais
simples com a adoção de métodos e técnicas analíticas dos dados.
Quando são usados modelos para a previsão de dados, são aplicadas técnicas analiticas, fundamentadas pela estatística e 
matemática para se obter estimativas mais precisas dos dados que está querendo prever.

Este é um trabalho de previsão de séries temporais agrícolas mais especificamente de indicadores de preços pecuários 
do Boi Gordo e Bezerro mensais. Ambas séries foram coletadas e podem ser encontradas facilmente do site da 
[CEPEA - Centro de Estudos Avançados em Economia Aplicada](https://www.cepea.esalq.usp.br/br).

A série referente aos preços do Boi Gordo é o principal indicador usado como base para criação e formação de preços 
para os contratos futuros do Boi Gordo da [B3](http://www.b3.com.br/pt_br/). Sobre a metólogia usada para criação deste 
indicador é feita uma média dos preços da arroba do boi gordo de todas as regiões do estado de São Paulo. 
Para poder encontrar mais informações referentes a métodologia utilizada para criação deste indicador acesse este 
[link](https://www.cepea.esalq.usp.br/upload/kceditor/files/Cepea_B3_Metodologia_Indicador_BOI_02_01_2020.pdf).

Como neste projeto foi utilizado a biblioteca Plotly para criar gráficos interativos para a análise de séries temporais
e o arquivo .ipynb e presente neste repositório não carrega os dados você visualizar os gráficos interativos por meio deste
[link](https://nbviewer.jupyter.org/github/bobcastaldeli/Prediction-Cattle-Price-CEPEA-B3/blob/master/Cattle-Time-Series.ipynb)
ou simplesmente clicando no título deste documento.

Para este projeto foram utilizados os seguintes pacotes:

* **Análise e manipulação de dados**
	* Numpy;
	* Pandas;

* **Visualização de Dados**
	* Matplotlib;
	* Seaborn;
	* Plotly;

* **Series Temporais e Métricas**
  * Statsmodels;
  * Scikit-Learn.
