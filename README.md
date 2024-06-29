# Data_Analytics--Frequencias_e_Medidas

Base de dados disponibilizado pela equipe da Owmakercode, com dados fictícios com a finalidade educacional de treino sobre o tema "Estatística, frequência e medidas" do curso Bootcamp Data Analytics 2024. 
Segue o escopo do trabalho. 

# Considerando a base de dados de enem_2023.json responda as questões
abaixo (os dados são fictícios).

Você é uma pesquisadora de um cursinho para estudantes que querem
ingressar na universidade em 2025. Seu objetivo é retirar informações da
base de dados do enem do ano anterior para alinhar melhor as estratégias do
cursinho para cada estudante.
O dado possui 6 colunas, 5 delas representam as disciplinas do ENEM e uma o
gênero das pessoas que fizeram a prova. No dado existe a representação de
1000 pessoas, sendo cada uma delas uma linha.
  1. Qual das disciplinas tem a maior amplitude de nota?
  2. Qual é a média e a mediana para cada uma das disciplinas? (Lembre-se
de remover todos os valores nulos quando considerar a mediana)
  3. Considerando o curso de Ciência da Computação da UFPE, onde o peso
cada uma das disciplinas ponderado:
  a. Redação - 2
  b. Matemática e suas Tecnologias - 4
  c. Linguagens, Códigos e suas Tecnologias - 2
  d. Ciências Humanas e suas Tecnologias - 1
  e. Ciências da Natureza e suas Tecnologias - 1
Qual o desvio padrão e média das notas dos 500 estudantes mais bem
colocados considerando esses pesos?
  4. Se todos esses estudantes aplicassem para ciência da computação e
existem apenas 40 vagas, qual seria a variância e média da nota dos
estudantes que entraram no curso de ciência da computação?
  5. Qual o valor do teto do terceiro quartil para as disciplinas de
matemática e linguagens?
  6. Faça o histograma de Redação e Linguagens, de 20 em 20 pontos.
Podemos dizer que são histogramas simétricos, justifique e classifique
se não assimétricas?
  7. Agora coloque um range fixo de 0 até 1000, você ainda tem a mesma
opinião quanto a simetria? [plt.hist(dado, bins=_, range=[0, 1000])
  8. Faça um boxplot do quartil de todas as disciplinas de ciências da
natureza e redação. É possível enxergar outliers? Utilize o método IQR.
  9. Remova todos os outliers e verifique se eles são passíveis de alterar a
média nacional significativamente? (considere significativamente um
valor acima de 5%)
  10. Considerando valores nulos, tente encontrar qual seria a melhor medida
de tendência que pode substituir as notas nulas. Média, moda ou
mediana? Substitua o valor por todos os três e diga qual delas altera
menos a média geral e o desvio padrão.

# Sugestões:
  - Abra o arquivo .ipynb com google colab (isso evitará alguma necessidade de instalação de programas adicionais)
  - Anexe o arquivo dos dados junto ao arquivo .ipynb para só depois iniciar a leitura dos códigos. 
  - Rode as células nas sequências aos quais elas foram escritas.
  - Faz parte do desafio manipular um arquivo .json, mas isso não será um problema pois no código existe uma célular exclusiva para tal. 

