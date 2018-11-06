# Cofactor_experimentos_BaseLine
Experimentos com o BaseLine.

Nós Gráficos apresentados nesse documento são apresentados alguns experimentos aplicados ao DataSet do BaseLine.

#### Descritivo dos DataSet's

1 - Orig_Cofactor: Compreende o DataSet Original. Possui valores que vão de 0 até o infinito. Quanto maior o valor maior a correlação entre os itens. Trata-se de um DataSet esparso, ou seja, é formado em sua maioria por valores nulos (0)

2 -  Norm_Cofactor: É uma normalização dos Dados do DataSet original. Os valores estão entre 0 e 1, quanto mais próximo de um for o valor, maior será a correlação entre os itens.

3 - Orig_DenseMatrix_RandomValue: Trata-se de uma modificação no DataSet original para torna-ló Denso, ou seja, é formado em sua maioria por valores não nulos (diferente de 0). Os valores que substituiem os nulos são gerados aleatoriamente.

4 - Norm_DenseMatrix_RandomValues: Trata-se de uma modificação no DataSet original para torna-ló Denso, ou seja, é formado em sua maioria por valores não nulos (diferente de 0). Os valores que substituiem os nulos são gerados aleatoriamente. Uma vez que o DataSet se torna denso ele é NORMALIZADO.

5 - Orig_DenseMatrix_05Values: Trata-se de uma modificação no DataSet original para torna-ló Denso, ou seja, é formado em sua maioria por valores não nulos (diferente de 0). Os valores que substituiem os nulos são fixados em 5.

6 - Norm_DenseMatrix_05Values: Trata-se de uma modificação no DataSet original para torna-ló Denso, ou seja, é formado em sua maioria por valores não nulos (diferente de 0). Os valores que substituiem os nulos são fixados em 5. Uma vez que o DataSet se torna denso ele é NORMALIZADO.

#### Resultados
Excetuando os resultados encontrado para o DataSet "5" que teve um desempenho muito ruim comparado ao BaseLine, todos os outros experimentos obtiveram resultados satisfatórios.

É possível verificar com os resultados que normalizar os dados tem uma influência bastante pequena sobre os resultados. Um  DataSet Denso porém normalizado tem resultados tão bom quanto o original.
