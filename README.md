# Beta Bank

## Descrição do projeto
Os clientes do Beta Bank estão saindo: pouco a pouco, escapulindo todo mês. Os banqueiros descobriram que é mais barato salvar os clientes existentes do que atrair novos.
Precisamos prever se um cliente deixará o banco em breve. Tenho os dados sobre o comportamento passado dos clientes e rescisões de contratos com o banco.
Construi um modelo com o valor máximo possível de F1. Para passar na revisão, o valor F1 deve ser pelo menos 0,59 para o conjunto de dados de teste.
Além disso, medi a métrica AUC-ROC e comparei-a com o valor F1.

## Instruções do projeto
1.	Examinei o equilíbrio das classes. Treinei o modelo sem levar em conta o desequilíbrio. 
2.	Melhorei a qualidade do modelo. Certifiquei-me de usar pelo menos duas abordagens para corrigir o desequilíbrio de classe. Usei conjuntos de treinamento e validação para encontrar o melhor modelo e o melhor conjunto de parâmetros. 
3.	Realizei o teste final.

## Descrição de dados
Características
-	RowNumber — índice das strings de dados
-	CustomerId — identificador exclusivo do cliente
-	Surname — sobrenome
-	CreditScore — pontuação de crédito
-	Geography — país de residência
-	Gender — gênero
-	Age — idade
-	Tenure — tempo de serviço para o cliente
-	Balance — saldo da conta
-	NumOfProducts — número de produtos bancários usados pelo cliente
-	HasCrCard — cliente possui cartão de crédito (1 - sim; 0 - não)
-	IsActiveMember — cliente ativo (1 - sim; 0 - não)
-	EstimatedSalary — salário estimado
Objetivo
-	Exited — o cliente saiu (1 - sim; 0 - não)
