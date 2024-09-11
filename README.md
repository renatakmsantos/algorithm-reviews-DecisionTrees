# algorithm-reviews-DecisionTrees

Objetivos do projeto:

1. Gerar uma árvore compacta (por exemplo, com até dois níveis no máximo) para o conjunto de dados.

2. Treine também os outros modelos, como Random Forest, Regressão Logística, Naive Bayes e kNN. 

3. Calcular a curva ROC dos modelos para comparar qual modelo foi mais bem sucedido para essa base de exemplos.

-------------

Dados: Default of Credit Card Clients
Previsão da Probabilidade de Inadimplência de Clientes de Cartão de Crédito

✨

Descrição: Esta base de dados contém informações sobre clientes de um banco em Taiwan, incluindo se eles falharam em pagar a fatura do cartão de crédito (default) no próximo mês.

Objetivo: Da perspectiva da gestão de risco, o resultado da precisão preditiva da probabilidade estimada de inadimplência será mais valioso do que o resultado binário da classificação - clientes confiáveis ​​ou não confiáveis. Mas para este trabalho será observada a curva ROC dos modelos para comparar qual modelo foi mais bem sucedido.

Características: 30.000 observações, 24 atributos e 1 chave de identificação (ID)

Dicionário Variáveis:

ID: Identificação de cada cliente

LIMIT_BAL: Montante de crédito concedido em dólares NT (inclui crédito individual e crédito familiar/suplementar)

SEX: Gênero (1=masculino, 2=feminino)

EDUCATION: (1=pós-graduação, 2=graduação, 3=ensino médio, 4=outros, 5=desconhecido, 6=desconhecido)

MARRIAGE: Estado civil (1=casado, 2=solteiro, 3=outros)

AGE: Idade em anos

PAY_0: Status de pagamento em setembro de 2005 (-1=pagamento em dia, 1=atraso de pagamento de um mês, 2=atraso de pagamento de dois meses, ... 8=atraso de pagamento de oito meses, 9=atraso de pagamento de nove meses ou mais)

PAY_2: Status de pagamento em agosto de 2005 (escala igual à acima)

PAY_3: Status de pagamento em julho de 2005 (escala igual à acima)

PAY_4: Status de pagamento em junho de 2005 (escala igual à acima)

PAY_5: Status de pagamento em maio de 2005 (escala igual à acima)

PAY_6: Status de pagamento em abril de 2005 (escala igual à acima)

BILL_AMT1: Montante da fatura em setembro de 2005 (dólar NT)

BILL_AMT2: Montante da fatura em agosto de 2005 (dólar NT)

BILL_AMT3: Montante da fatura em julho de 2005 (dólar NT)

BILL_AMT4: Montante da fatura em junho de 2005 (dólar NT)

BILL_AMT5: Montante da fatura em maio de 2005 (dólar NT)

BILL_AMT6: Montante da fatura em abril de 2005 (dólar NT)

PAY_AMT1: Montante do pagamento anterior em setembro de 2005 (dólar NT)

PAY_AMT2: Montante do pagamento anterior em agosto de 2005 (dólar NT)

PAY_AMT3: Montante do pagamento anterior em julho de 2005 (dólar NT)

PAY_AMT4: Montante do pagamento anterior em junho de 2005 (dólar NT)

PAY_AMT5: Montante do pagamento anterior em maio de 2005 (dólar NT)

PAY_AMT6: Montante do pagamento anterior em abril de 2005 (dólar NT)

default.payment.next.month: Inadimplência no pagamento (1=sim, 0=não)
