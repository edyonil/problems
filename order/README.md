# Situação

Tem uma lista que vem ordenado pelo Pai e necessário gravar em uma base de dados relacional. Se vocês analisarem a ordem
que os dados estão vai perceber, por exemplo, que o filho 10 depende da inclusão do Pai 6, que não foi incluído ainda. 
Assim é necessário salvar os dados do 6 primeiro para depois salvar os filhos do 6.

O objetivo é que no final todos os dados tenham sido salvos!
