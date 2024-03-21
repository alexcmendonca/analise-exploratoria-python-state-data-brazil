# State of Data Brazil 2022 - Análise Exploratória de Dados: Descobrindo Tendências no Mercado de Dados

## 💡Contexto
O **State of Data Brazil** ([link](https://www.bain.com/contentassets/16494c60fcd045188615f05e728385b3/state-of-data2022_um-raio-x-dos-profissionais-de-dados-do-brasil.pdf)), realizada pelo [Data Hackers](https://www.datahackers.com.br/) e pela [Bain & Company](https://www.bain.com/), é uma das
maiores pesquisas sobre o mercado brasileiro de dados. Dentre os assuntos pesquisado na
última pesquisa (2022), foi mapeado o peral atual das três maiores proassões da área de
dados do Brasil: **engenheiro de dados**, **cientista de dados** e **analista de dados**. O relatório
completo pode ser acessado neste [link](https://www.stateofdata.com.br/).

###### Imagem 1: Remuneração em 2022 por nível de cargo
<img src="grafico-stateofbrazil-2022.png">


## 🖥️Objetivo
O objetivo principal deste projeto é identificar e analisar a média de salários no mercado de dados, levando em consideração os cargos (Analista, Cientista e Engenheiro de Dados) e seus níveis de experiência. Por meio desta análise, descobrir tendências significativas e insights valiosos que possam auxiliar profissionais, empresas e pesquisadores no entendimento do panorama salarial neste campo em constante evolução.


##  🗂️Organização dos Arquivos Databricks e Data Factory
* Notebooks | Databricks
    - Transformações nos dados e salvando-os em um arquivo Delta Lake no repositório Azure Data Lake.

* Factory | Azure Data Factory
    - Arquivos de configuração carregados no repositório GitHub após conexão Data Factory

* Databricks-pcm
    - Arquivos de configuração da conexão do Databricks ao Data Factory

* Pipeline
    - Arquivos de configuração do pipeline

* Trigger
    - Arquivos de configuração do gatilho de execução

## 🎞️Imagens do Projeto

###### Imagem 5: Monitorando execução do pipeline no Data Factory
<img src="/img/monitorando-execucao-pipeline.png">

###### Imagem 6: Monitorando execução do pipeline no Databricks / Job runs
<img src="/img/monitorando-execucao-pipeline-databricks.png">

###### Imagem 7: Tela inicial do estúdio Azure Data Factory
<img src="/img/estudio-azure-data-factory.png">

## 🔍Referências
- [Alura](https://www.alura.com.br/)