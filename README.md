# Stock Classification (Clustering)
Classificação de títulos de bolsa nacionais e internacionais com base em Cluster K-Means

O intuito deste trabalho é encontrar as melhores acções de bolsa a nível "mundial", através dos seus indicadores de retorno e volatibilidade dos últimos dois anos. 
Além do agrupamento dos títulos por diferentes quadrantes dos indicadores citados, faço uma escolha de alguns com base dos seus valores actuais em bolsa, eventualmente para aquisição.

O trabalho passa por diferentes métodos de Data Science e é todo realizado em Python:
* inicia com a obtenção de dados através de Web Scrapping, 
* tratamento dos mesmos em Pandas,  
* aplicação do modelo de classificação K-means, desde a descoberta do melhor número de clusters ("k") até à sua aplicação
* remoção de outliers
* selecção das melhores acções com retorno anual igual ou acima de 10% e volatibilidade abaixo de 40% (escolha pessoal!)
* obtenção dos preços actuais dos títulos da alínea anterior
* amostragem final das "melhores" acções em diferentes colorações consoante o seu preço

Elbow curve - seleção do número de clusters K-means:
![image](https://github.com/JorgeGomes72/StocksClassification/assets/57633568/82aec309-911d-42ab-bbde-04baab05122e)


Classificação de títulos com 3 Clusters face ao Retorno e Volatilidade Anual:
![image](https://github.com/JorgeGomes72/StocksClassification/assets/57633568/64a3d1e4-7b06-4b81-bed4-9c91ea6e79d1)

 
Remoção de Outliers:
![image](https://github.com/JorgeGomes72/StocksClassification/assets/57633568/9e6a7183-1919-4bc6-9b92-9ecb4f8f46f9)

 
Títulos com Rentabilidade acima de 10% ao ano e Volatilidade inferior a 40%:
![image](https://github.com/JorgeGomes72/StocksClassification/assets/57633568/92a54e3b-0208-4d47-b934-78d455670b9a)

 
Seleção de títulos com preços abaixo de 50€: 
![image](https://github.com/JorgeGomes72/StocksClassification/assets/57633568/a55f20c0-8818-49df-965d-c7abfa5961ca)



Por fim, se o investimento não resultar não me culpem, sou um mero Data Scientist!

Trabalho realizado tendo por base o seguinte artigo:
"
Stock classification using k-means clustering, de Facundo Joel Allia Fernandez
"

