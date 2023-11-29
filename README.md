# StocksClassification
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

Por fim, se o investimento não mostrar vir a ser o melhor não me culpem, sou um mero Data Scientist!
