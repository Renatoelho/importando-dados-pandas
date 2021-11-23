# Importando dados com Pandas 

Pandas é uma biblioteca da linguagem Python muito utilizada para análise de dados, trabalha com a manipulação de <i>Dataframes</i>, que são estruturas de dados em formato de tabelas e séries temporais. A biblioteca é muito usada pela comunidade de análise de dados e <i>Data Science</i>. 

O nome pandas vem da junção dos prefixos das palavras <i>panel data</i>, termo em inglês que é usado por profissionais de estatística que refere-se à amostra de dados.

Um <i>Dataframe</i> é criado a partir de uma base externa, que pode ser um banco de dados <i>SQL</i> e/ou <i>NoSQL</i> ou até mesmo arquivos como: <i>txt, xls, csv</i> entre outros. Essa é a primeira etapa para quem vai usar o pandas para analisar dados.

No nosso exemplo aqui vamos importar uma base de clientes a partir de um arquivo ````.csv````, mas a lógica aplicada aqui pode ser feita para outros tipos de arquivos. 

>> Consulte a documentação do Pandas que você terá mais ajuda em relação aos arquivos que podem ser importados.

Na documentação do repositório teremos a [base de clientes](BaseClientes.csv) o [Jupyter notebook](import_csv_pandas.ipynb) e as demais informações necessárias para você replicar o apresentado aqui na sua máquina de desenvolvimento.

Essa base de clientes tem 5 colunas e 1000 linhas e vamos importar usado o comando ````read_csv()```` existente no Pandas.

```Python

import pandas as pd

base_clientes = pd.read_csv('BaseClientes.csv', delimiter=',')

base_clientes

```

![Importe arquivo CSV](https://drive.google.com/uc?export=view&id=1tYQOIhOwDHozhwhbYcTKmiCVBuOFqkC1)

Um comando muito simples, mas que é o primeiro passo para você trabalhar com o Pandas.

Em breve volto com novos tutoriais sobre o **Pandas** e como usá-lo para manipular dados.

**Até lá.**

**Referências:**  <br/><font size="1">Wikipedia, **pandas (software).** Disponível em: <https://pt.wikipedia.org/wiki/Pandas_(software)>. Acesso em: 05 mai. 2021.   <br/>Pandas, **User Guide.** Disponível em: <https://pandas.pydata.org/docs/user_guide/index.html>.  Acesso em: 05 mai. 2021.   <br/>Pandas, **pandas.read_csv().** Disponível em: <https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html#pandas.read_csv>. Acesso em: 05 mai. 2021.   <br/></font>

