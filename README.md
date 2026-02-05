# Aviso

Material produzido acompanhando um curso aberto. O conteúdo original não é meu e não deve ser redistribuído.

# Geral

A unidade trata de bancos de dados não relacionais.

## Por que surgiram

Três fatores costumam ser citados:

- O volume de dados armazenados dobra a cada ano, segundo estimativas de especialistas;
- Cada vez mais aplicações têm comportamento que não encaixa no modelo tabular;
- A demanda por escalabilidade cresceu muito.

As limitações dos bancos relacionais nesses cenários abriram espaço para as alternativas.

## Relacional versus não relacional

### Escalabilidade

Bancos relacionais tendem a crescer na vertical, enquanto os não relacionais crescem na horizontal — embora estes também possam escalar verticalmente. Existem casos de bancos relacionais com escala horizontal, mas normalmente ligados a leitura. A distribuição de dados entre réplicas no mundo não relacional recebe um nome próprio: fragmentação.

Como a escala horizontal é mais simples nesse modelo, variações bruscas de carga são absorvidas com menos dor.

### Estrutura

No modelo relacional é preciso definir tabelas, relações e tipos antes de começar. No modelo não relacional, quase não há estrutura obrigatória na origem.

### Linguagem

Bancos relacionais usam a linguagem de consulta padrão; os não relacionais normalmente não usam — ou usam variantes próprias.

### Desempenho

No relacional, ganho de desempenho costuma vir de hardware melhor. No não relacional, costuma vir do tamanho do cluster e da qualidade da rede entre os nós.

### Transações

Veja a imagem:

![transações](images/differences-sql-nosql-transactions.png)

Em geral, os bancos não relacionais não trabalham com o conceito de transação, com exceção do MongoDB. A ausência é justamente o que ajuda a manter disponibilidade e desempenho.

### Vantagens

- Flexibilidade;
- Escalabilidade;
- Desempenho alto.

## Tipos de banco não relacional

O ponto comum entre os vários tipos é justamente não depender da linguagem de consulta padrão. A imagem abaixo mostra um ranking de popularidade entre os bancos:

![ranking](images/ranking-of-databases.png)