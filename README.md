# Formato do Arquivo
The DataSet contains historical sales data for 45 Amazon stores located in different regions.
SUMMARY
Dataset Description

The DataSet contains historical sales data for 45 Amazon stores located in different regions. Each store contains a number of departments, and have to predict the department-wide sales for each store.

In addition, Amazon runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the Dataset is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.

This file contains anonymized information about the 45 stores, indicating the type and size of store.

This is the historical training data, which covers to 2019-02-05 to 2021-11-01. Within this file you following are the different fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales - sales for the given department in the given store IsHoliday - whether the week is a special holiday week Temperature - average temperature in the region Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Amazon is running. MarkDown data is only available after Nov 2020 and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate
For convenience, the four holidays fall within the following weeks in the dataset (not all holidays are in the data):

Super Bowl: 12-Feb-19, 11-Feb-20, 10-Feb-21, 8-Feb-18

Labor Day: 10-Sep-19, 9-Sep-20, 7-Sep-21, 6-Sep-18

Thanksgiving: 26-Nov-19, 25-Nov-20, 23-Nov-21, 29-Nov-18

Christmas: 31-Dec-19, 30-Dec-20, 28-Dec-21, 27-Dec-18



===== PT-BR

"O DataSet contém dados de vendas históricas para 45 lojas da Amazon localizadas em diferentes regiões. Cada loja contém vários departamentos e temos que prever as vendas de toda a loja para cada departamento.

Além disso, a Amazon realiza vários eventos promocionais de descontos ao longo do ano. Esses descontos precedem feriados proeminentes, sendo que as semanas que incluem esses feriados têm peso cinco vezes maior na avaliação do que as semanas não feriadas. Parte do DataSet é modelar os efeitos dos descontos nessas semanas de feriado na ausência de dados históricos completos/ideais.

Este arquivo contém informações anonimizadas sobre as 45 lojas, indicando o tipo e o tamanho da loja.

Estes são os dados de treinamento histórico, que abrangem de 05/02/2019 a 01/11/2021. Dentro deste arquivo estão os diferentes campos:

Loja - o número da loja
Departamento - o número do departamento
Data - a semana
Vendas Semanais - vendas para o departamento especificado na loja especificada
IsHoliday - se a semana é uma semana de feriado especial
Temperatura - temperatura média na região
Preço do combustível - custo do combustível na região
MarkDown1-5 - dados anonimizados relacionados a descontos promocionais que a Amazon está realizando. Os dados de desconto estão disponíveis apenas após novembro de 2020 e nem sempre estão disponíveis para todas as lojas. Qualquer valor ausente é marcado com um NA.
IPC - índice de preços ao consumidor
Desemprego - a taxa de desemprego

Para conveniência, os quatro feriados caem nas seguintes semanas no conjunto de dados (nem todos os feriados estão nos dados):

Super Bowl: 12 de fevereiro de 2019, 11 de fevereiro de 2020, 10 de fevereiro de 2021, 8 de fevereiro de 2018
Dia do Trabalho: 10 de setembro de 2019, 9 de setembro de 2020, 7 de setembro de 2021, 6 de setembro de 2018
Ação de Graças: 26 de novembro de 2019, 25 de novembro de 2020, 23 de novembro de 2021, 29 de novembro de 2018
Natal: 31 de dezembro de 2019, 30 de dezembro de 2020, 28 de dezembro de 2021, 27 de dezembro de 2018"
</p>
</p>
</p>
</p>
# Exemplos de Prompts
</p>
</p>

  Quais são os insights sobre padrões observados nos dados do arquivo https://raw.githubusercontent.com/vitormariath/Amazon-UK-Sales-Data-Set/main/amazon_sales_dataset_2020-21.csv.
Demonstre previões com base em tendências atuais e explore hipoteses.
Sendo que as variáveis do arquivo são: Date,Store,Dept,,Weekly_Sales,Type,Size,Temperature,Fuel_Price,CPI,Unemployment,IsHoliday,Year,Month,Week,max,min,mean,median,std,Total_MarkDown
</p>
</p>

Realize a análise de tendência de vendas por semana considerando a variação do CPI, com python para ser executado no Google Colab do arquivo em https://raw.githubusercontent.com/vitormariath/Amazon-UK-Sales-Data-Set/main/amazon_sales_dataset_2020-21.csv. 
# Sendo que as variáveis do arquivo são: Date,Store,Dept,,Weekly_Sales,Type,Size,Temperature,Fuel_Price,CPI,Unemployment,IsHoliday,Year,Month,Week,max,min,mean,median,std,Total_MarkDown
