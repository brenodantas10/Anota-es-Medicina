O DNA é o código da vida e possui a informação da construção de várias proteínas. A partir da análise dele e de outras estruturas informacionais como RNA é possível diagnósticar algumas doenças genéticas.
A área de estudo dessa área faz parte da **Biologia Molecular**

# Biologia Molecular
Auxilia no diagnóstico ou prognostio de doenças genéticas, infecciosas e câncer.

## O Diagnóstico

```mermaid
graph LR
	A[DNA]
	B[RNA]
	C[Proteína]
	D[Identificação clínica]
	A --> B
	B --> C
	C --> D

```

### Análises clínicas
```mermaid
graph TB
	A[Fluidos]
	B[Dosagem]
	C[Diagnostico]
	A --> B
	B --> C

```
Usada em medicina **curativa**

### Biologia molecular
```mermaid
graph TB
	A[Material genético e produtos de expressão]
	B[DNA ou RNA ou proteínas]
	C[Diagnóstico precoce]
	A --> B
	B --> C

```
Usada em medicina **preventiva**

## Diagnóstico Molecular

### Em nível de DNA
- Avaliação do genoma
- Cromossomos (citogenética)
- Sequências de DNA
- [[Polimorfismos]], deleções e inserções

### Métodos
- PCR
- RFPL
- Southern blot
- Sequenciamento

# Diagnóstico de Doenças
- Será que pessoas que convivem com pessoas contamidadas com uma doença contagiosa e nunca pegaram a doença são imunes por causa de alguma causa molecular?
	- Algumas explicações podem estar nos SNPs.
- Diabetes tipo 1
	- Existe uma relação entre a VTNR e a diabetes. Quando a repetição de um determinado gene abaixo de 43 repetições há uma boa chance de diabetes tipo 1.

## Técnicas
- Microarrays
	- Promove uma visualização da expressão gênica
	- Ex.: Caracterização transcritômica do câncer de mama

# Técnicas de Análise

## DNA
- Coleta de amostras
- Sangue ou medula óssea: anticoagulante EDTA, 4ºC por até 48 h.
- Tecidos frescos: processar em seguida ou armazenar a -80ºC


- Enzimas de restrição
- Eletrofosese
- Identificação do gene (Sondas)

### *Southern blotting*
- Existem proteínas que reconhecem determinados setores do DNA e recorta essas partes
	- Se esses setores forem alterados, as proteínas de corte nã serão mais identificadas e, então, não haverá o corte.
- Esses recortes, então, são puxados pela eletroforese.
- A técnica faz então uma leitura dessas regiões e tentam reconhecer pelo tamanho/grossura da banda vista para ver se não tem algum fragmento que está maior que o outro
	- A anemia falciforme há uma junção de uma banda de 1150 e de 200 em uma de 1350, pois a codificação do ponto de corte foi alterado e não pode ser identificada pela proteína de corte.

### PCR
- Replicação por RNA polimerase
- Faz-se uma replicação em ritmo exponencial
- o processo chega a cerca de 100ºC, necessitando da proteínas de seres de regiões extrema
	- A temperatura desnaturaria as proteínas humanas
- A única necessidade é ter o **primer** do gene que quer codificar
- A técnica do PCR irá replicar esse trecho várias vezes, sem ser necessário utilizar sondas para identificar o gene, pois se sabe que só existe o que quer analisar.

- Novas técnicas com base na PCR
	- RT-PCR
		- Processos de replicação mais rápidos
	- PCR Multiplex
	- qPCR
		- Não necessita de gel, tudo é quantificado computacionalmente
		- Reconhece o comprimento de onda refletido pela substância e quantifica pela intensidade do retorno

### Sequenciamento de Didesoxi (de Sanger)
- Define precisamente as sequencias de DNA, podendo identificar alelos normais e mutantes.
- Objetiva criar uma biblioteca

- Utilizando a técnica de didesoxi, cada alelo é pintado com uma cor
- A retiragem de dois oxigênios da moléculo causa uma paragem/separação da molécula de DNA
- Uma máquina lê essas sequências para mapeá-las.

## RNA
- Aplicações
	- Expressão diferencial de mRNA em determinadas patologias
	- Expressão diferencial em células tratadas
	- Ação de drogas

- Atuações
	- Câncer de próstata (PCA3)

### Biochips de DNA
- Um chip com sondas de voltadas para genes alvo
- Esses chips vão conter o DNA que vai começar a ter expressão gênica
- A intensidade da expressão vai ser lida por um computador.
	- Há uma coloração de genes bons e genes ruins
	- Há um cruzamento com o DNA sendo visto
	- A quantidade de genes bons e ruins vai determinar o prognóstico

### Western Blot
Utiliza anticorpos marcados radioativamente para detectar a expressão da proteína de interesse

- Pode-se utilizar em:
	- Distrofia Muscular
		- A partir da análise da distrofina
			- Sem distrofina = Duchenne
			- Com distrofina anormal = Becker

