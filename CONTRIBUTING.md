# Colaboração

## 1. Padrões para texto simples

### 1.1. Espaçamento

O título deve estar separado do texto por uma linha.

As estrofes devem estar separadas entre si por três linhas.

Os pares [verso e acordes] devem estar separados entre si por uma linha.

### 1.2. Extensão das sílabas

Se a sílaba for menor do que o nome do acorde, ela de ser estendida com o símbolo `_` até que tenha o mesmo tamanho.
```
A7sus4
Pai,__
```

### 1.3. Extensão dos versos

Preferencialmente, os versos devem ter a extensão indicada na métrica do hino.

## 2. Padrões para notação ABC

### 2.1. Cabeçalho

* **X**: Número com três dígitos (001, 005, etc.)
* **T**: Título (pode ser repetido para diferenciar primeira e segunda música)
* **M**: Fórmula de compasso (3/4, 4/4, etc.)
* **L**: Unidade de duração básica (1/8, 1/4, etc.)
* **K**: Tom (A, Cm, etc.)
```
X:005
T:Trindade adorada
T:(Primeira música)
M:4/4
L:1/4
K:G
```

### 2.2. Dois acordes em uma nota

Embora seja possível registrar dois acordes na mesma nota, esse formato impede o funcionamento correto da transposição. O segundo acorde não é reconhecido e, consequentemente, não é alterado.
```
"A7sus4 A7" A4
```
Para evitar esse resultado, é possível dividir a nota em duas, uní-las com ligadura e registrar um acorde em cada uma das notas resultantes.
```
"A7sus4" A2- "A7" A2
```
O alinhamento da letra deve ser mantido utilizando o símbolo `~`.