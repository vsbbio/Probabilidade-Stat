# Probabilidades e Estatísticas
## Parte 1

### Probabilidade: 

1. Quantificação do conhecimento acerca de um evento particular;
2. **É medida da informação ou *crença* sobre a ocorrência do evento.**


#### 1.01 Definição Clássica, eventos equiprováveis: Razão entre m/n

p = m/n , onde:
  p = razão / probabilidade de ocorrência
  m = número de resultados favoráveis
  n = numero de resultados possíveis

#### 1.02 Definição Frequencialista: Utilizando o histórico do que já aconteceu probabilidade assume o limite da frequência relativa m/n

lim m/n,  onde:
n-∞

m = número de vezes que ocorreu o evento
n= número de experimentos

#### 1.03 Definição Axiomática: Probabilidade é um número vinculado a um evento que respeita as seguintes leis:

1. P(E) >= 0
2. P(S) = 1
3. P(E U F) = P(E) + P(F), **se os eventos são mutuamente exclusivos**

### Outras definições:

1. **A probabilidade de eventos complexos é cálculado a partir dos eventos elementares, sendo estes calculados a partir de cada definição acima**

2. **Espaço Amostral = Conjuntos de todos os resultados possíveis de um particular experimento;**

3. **Eventos Mutuamente Excludentes: A Π B = 0 = vazio**

## Parte 2 - Teoremas de probabilidade

### Evento Complementar

Ā = Eventos que não estão contidos em A
P(Ā) = 1 - P(A)

### Teorema da União

P(A U B) = P(A) + P(B) - P(A Π B)

### Probabilidade Condicionada: Probabilidade de A relativa ao subespaço B

P( A | B) = P(A Π B) / P(B)

### Teorema do Produto/Intersecção:

1. Eventos Não Independentes:
** P(A Π B) = P(A) * P(B | A)**

Generalização do Teorema para o caso de 3 eventos (A, B e C)
** P(A Π B Π C) = P(A) * P(B | A) * P(C |A Π B)**

2. Eventos Independentes:

A Informação sobre o evento A não altera a probabilidade de ocorrência de B: **P(B | A) = P(N)**
Portanto, teorema do produto fica simplificado:

**P( A Π B) = P(A).P(B)**
