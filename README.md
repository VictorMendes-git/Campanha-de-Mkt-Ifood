# Análise de campanha de Marketing Ifood

# Problema de negócio 
iFood é o principal aplicativo de entrega de comida no Brasil, presente em mais de mil cidades. 

Manter um alto engajamento do cliente é fundamental para o crescimento e a consolidação da posição da empresa como líder de mercado. Analistas de dados que trabalham na equipe de dados são constantemente desafiados a fornecer insights e valor para a empresa por meio de projetos.

Este caso pretende simular isso. Neste caso, você é apresentado a um conjunto de dados de amostra sobre o cliente e as interações da campanha iFood com esse cliente. É seu desafio entender os dados, encontrar oportunidades e insights de negócios e propor qualquer ação orientada a dados para otimizar os resultados das campanhas e gerar valor para a empresa. 

Como analista de dados, o seu objetivo é:
Fazer uma análise descritiva dos clientes com base nos comportamentos, a fim de encontrar características que permitam à empresa maximizar o lucro da próxima campanha de marketing.

# Contexto 
O time de Marketing do Ifood faz campanhas recorrente para aumentar o faturamento da empresa. Porem existe uma necessidade de entender as ações que ttrouxeram resultados positivos e negativos para aprender e replicar nas campanhas futuras.

Nesse contexto, o Analista de dados tem um papel fundamental para coletar, analisar e gerar Insights para o time de negócio, a fiom de ajuda-lo a ter melhores resultados.

# Premissas da análise 
1. A campanha aconteceu emtre 15 de Janeiro de 2025 até 30 de janeiro de 2025.
2. Todos produtos comprado com cupom foram removidos.
3. A análise considerou somente os produtos do catalogo da campanha. 

# Estrategia da solução 
O método usado para a analise da campanha foi Fato-dimensão.

## Passo 1 : Resumir o contexto em uma pergunta aberta 
As perguntas abertas são um tipo de demanda muito comum em analise de dados no qual a demanda possui N possiveis soluções e cabe ao analista de dados avaliar as possibilidades e escolher as alternativas com maior retorno e o menos esforço possivel. Para essa análise foi definida a segunte pergunta aberta:

**Como aumentar aumentar o resultado da próxima campanha de Marketing?**

## Passo 2 : Transformar pergunta aberta em fechada 
As perguntas fechadas são um tipo de demanda muito comum na área de análise de dados. Essa demanda contém todos os detalhes da análise de dados e direciona o analista exatamente para o que precisa ser feito. Geralmente, a pergunta fechada é a escolha de uma solução entre todas as alternativas possíveis, feita por um profissional mais Sênior da área.

Para essa análise foi definida a seguinte pergunta fechada:
**Quais são as caracteristicas dos clietes que mais gastaram na campanha de Marketing?**

## Passo 3 : Definição da coluna Fato 
O Fato é coluna de interesse que representa o ponto focal da análise. Nesse caso, a coluna 'Gasto-Clientes' representa o faturamento de cada cliente dentro da campanha e será o objetivo da nossa análise, dado que o problema de negócio envolve aumento do faturamento na próxima campanhas de Marketing.

## Passo 4 : Indentificações das dimensões 
As colunas foram agrupas em dimensões comuns que fornecem mais detalhes sobre o Fato que será analisado. Foram organizadas as seguintes dimensões:

1. Cliente
- Salário
- Idade
- Faixa-Etária
- Dias-Cliente
- Estado-Civil
- Formação
- Crianças-Casa
- Adolescentes-Casa
- Recência

2. Produto
- Qtde-Vinhos
- Qtde-Frutas
- Qtde-Carnes
- Qtde-Peixes
- Qtde-Doces
- Qtde-Premium
  
2. Comportamento de Compra
- Qtde-Compras
- Qtde-Compras-Web
- Qtde-Compras-Loja
- Visitas-Site-Mes

4. Comportamento de Mkt
- Reclamações.
  
## Passo 5 : Hipóteses analíticas
Fato (Medida) + Dimensão (Detalhes) + Comparação

As hipóteses analíticas são construídas a partir da combinação do fato com as dimensões, usando sempre um valor de comparação como maior, menor ou igual

Fato + Dimensão: Cliente – Atributos: Idade

1. O faturamento dos clientes **abaixo de 30 anos** é maior do que nas outras faixas etárias.  
2. O faturamento dos clientes **entre 20 e 30 anos** é maior do que nas outras faixas etárias.  
3. O faturamento dos clientes **acima de 30 anos** é maior do que nas outras faixas.  

Fato + Dimensão: Cliente – Atributos: Estado Civil

4. Clientes solteiros gastam mais do que os outros segmentos de clientes.  
5. Clientes solteiros gastam menos do que os outros segmentos de clientes.  
6. Clientes casados gastam mais do que os outros segmentos de clientes.  

Fato + Dimensão: Cliente – Atributos: Estado Civil + Idade

7. Clientes solteiros acima dos 30 anos gastam mais do que clientes casados acima dos 30 anos.  

Fato + Dimensão: Cliente – Atributos: Formação Profissional

8. Clientes com formações avançadas (Doutorado) gastam mais do que clientes com Ensino Fundamental.  
9. Clientes com maiores salários têm nível de escolaridade maior.  

## Passo 6 : Critérios de priorização 
Critério 1: Dados disponíveis

Critério 2: Insights acionáveis

## Passo 7 : Priorização das Hipóteses 

# Insights da análise 

# Resultado 

## Visualização da análise completa 
