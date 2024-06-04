Primeiramente, utilizando a biblioteca de software pandas e a IDE do proprio Google Collab foi criado um dataframe sobre filmes indicando nome, diretor, duração entre outras informações

Após isso para completar a segunda questão eu utilizei o comando shape para que fosse mostrado o tamanho do meu dataframe sendo "tamanho[0]" representando o numero de linhas e "tamanho[1]" representando o numero de colunas.

Para a terceira questão foi expecificado primeiramente um numero para que fosse definido qual linha ele iria buscar e com isso utilizamos o "iloc[x]" para que fosse apresentando a linha correspondente ao x (2 ou Que Horas Ela Volta).

Para a quarta questão utilizamos o empty para dizer se o dataframe é vazio ou não, retornando um valor boleano.

Para a quinta questão utilizamos o head(5) para especificar quais linhas queremos apresentar em nosso output (neste caso sendo as 5 primeiras linhas)

Para a sexta questão utilizamos o drop para apagar o filme Avatar.

Para a setima questão criamos um novo dataframe com o filme que gostaremos de inserir no dataframe principal. E para uni-los utilizamos o comando concat para que possam ser "concatenados"

Para a oitava questão utilizamos o transpose para trocarmos as linhas e colunas de lugar invertendo seu design

Para a nona questão utilizamos o iloc novamente para escolhermos quais colunas e quais linhas iremos apresentar sendo respectivament e apresentanda colunas 0 até 2 (: antes da virgulha é linhas e depois é a quantidade de colunas no caso do exemplo :,:2 respectivamente todas as linhas e duas colunas)
