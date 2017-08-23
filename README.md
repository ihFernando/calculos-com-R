# Linguagem R
Estudo: Linguagem R

Programa: R v-3.1.2

## Introdução a Estatística

### Tipos de dados

##### Dados Categóricos
É o tipo de dado que baseia-se em categorias e não tem uma ligação direta, um dado não é melhor que o outro e vice-versa

Exemplo: Masculino ou Feminino

##### Dados Ordinais
Quando os intervalos não tem um valor exato. Uma sequência que não conseguimos ter certeza da diferença entre os valores.

Exemplo: 1 - 10

##### Dados Intervalares
São dados que a diferença entre os valores são exatas. A diferença entre os números são precisas.

Exemplo: 50° - 55°

### Histograma
É um gráfico que mostra a quantidade de frequência em que os valores se repetem

### Outliers 
São definidos como pontos fora da curva

Em um distribuição onde os valores são:
**"1
1
2
3
40"**

O 40 é um ponto fora da curva.

### Diferença entre Média, Mediana e Moda
Média: Me retorna a tendência central da sequência (Utilizar quando os valores estiverem melhor distribuídos);

Mediana: É o elemento que está localizado no meio da distribuição, quando ela está ordenada (Não é tão afetada pelos outliers);

Moda: Elemento que mais se repete na distribuição.

### Divisão por Quartis
Pegamos a distribuição e dividimos em três partes, 25% do inicio, 25% do fim e usamos 50% do meio.

Em uma distribuição com 12 números:

3-3-4-6-7-8-10-11-11-12-12-30 (Distribuição)

12/4 = 3 (Definindo os 25% iniciais e finais da distribuição)

Ficando com:

3-3 = 25% (Iniciais)

4-6-7-8-10-11-11-12 = 50% (Valores para trabalhar)

12-30 = 25% (Finais)

### Boxplot
É uma representação gráfica para entendermos como está a distribuição entre o maior, menor e os dados do meio. Podemos utilizar até a mediana dentro do Boxplot.

### Observações
Dados tem sujeiras, limpar os dados faz com que o trabalho com deles seja mais exato.

## Comandos R

?+comando = mostra manual de como usar o comando
open+nome arquivo = abre arquivo

### Atribuindo lista a variável: 

lista <- c(numeros da lista)

### Comando: hist(lista)

Gera um histograma de uma lista

### Comando: Summary 

Retorna as informações sobre a distribuição de números.
summary(lista)

Min. - 1st Qu. - Median - Mean - 3rd Qu. - Max.

### Comando: Boxplot

Retorna dados em gráfico

boxplot(numeros)

### Comando: Png

Converte um gráfico em imagem no formato png

png(file="caminha do arquivo/nome.png", width=500, height=500)

### Comando: dev.off()

Conclui a tarefa de boxplot

### Comando: var(lista)

Retorna a variância de uma distribuição

### Comando: sqrt(lista)

Calcula a raiz quadrada de um numero

### Comando: sd(lista)

Calcula o desvio padrão de uma distribuição

### Comando: read.csv(file="arquivo.csv")

Lê um arquivo do tipo **csv** para poder trabalhar com ele

### Comando: cor()

Calcula a correlação entre dois números

cor(a, b, method="pearson" ou method="spearman")

