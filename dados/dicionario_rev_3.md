DICIONÁRIO DE DADOS: 

train_id - Variável do Tipo int64: Coluna referente Identificação numeral da posição que foi cadastrada no data set, semelhante a função do INDEX, (não está em ordem referente a data de venda).

test_id - Variável do Tipo int64: Coluna referente Identificação numeral da posição que foi cadastrada no data set, semelhante a função do INDEX, (não está em ordem referente a data de venda).

name - Variável do Tipo object: Coluna na qual contem a TAG do produto. Palavras chaves ou texto utilizados identificar e localizar o produto.
item_condition_id - Variável do Tipo int64: Coluna contendo a condição do produto, numeração fornecida pelo vendedor. Sendo: 1 com uma melhor condição e a 5, é o que apresenta uma pior condição.

category_name - Variável do Tipo object: Coluna contendo a categoria do produto. A primeira palavra é a categoria principal, e a última palavra é a categoria que o produto se encontra.

main_cat - Variável do Tipo object: Coluna é resultado da separação da coluna category_name, seus dados consistem na primeira palavra e contempla a categoria principal.

sub_cat1 - Variável do Tipo object: Coluna é resultado da separação da coluna category_name, seus dados consistem na segunda palavra e contempla a primeira ramificação da main_cat.

sub_cat2 - Variável do Tipo object: Coluna é resultado da separação da coluna category_name, seus dados consistem na terceira palavra e contempla a primeira ramificação da sub_cat1.

brand_name - Variável do Tipo object: Coluna contendo a marca do produto.

shipping - Variável Tipo int64: Coluna referente a frete, no qual CIF = 1 (taxa de envio paga pelo vendedor), FOB = 0 (taxa de envio para pelo comprador).

item_description - Variável do Tipo object: Coluna contém a descrição da característica do produto, informação fornecida pelo vendedor. 

date - Variável do Tipo object: Coluna contendo a data da inserção do produto.

stock - Variável do Tipo object: (Esse me gerou dúvidas:  esse é o estoque do produto no dia da inserção.

PALAVRAS CHAVES:

Vendedor - Empresa/pessoa responsável pelo produto anunciado.
