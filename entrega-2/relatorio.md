# Relatório da Entrega 2 de Estudos Avançados em Sistemas de Software (10/04/2025)

Nome: David Tadokoro\
NUSP: 10300507\
Orientador: Paulo Meirelles\

<br>

## 1) Contexto

No primeiro semestre de 2024, houve o oferecimento da disciplina de
*Desenvolvimento em Software Livre* (MAC0470/5856). Grande parte da disciplina
envolveu mentorar os alunos para contribuírem para algum subsistema do kernel
Linux (o subsistema do _Industrial I/O_, no caso), partindo desde a construção
de um ambiente de testes até o envio do patch e participação no processo de
revisão. Neste primeiro semestre de 2025, a disciplina está sendo ofertada
novamente nos mesmos moldes.

O projeto proposto para a disciplina envolve a escrita de um artigo científico
sobre o fenômeno de entrada de novatos no kernel Linux, e como mentorá-los de
uma forma eficiente e prática.

Nesta segunda entrega, o objetivo era organizar as observações dos monitores e
do professor em relação ao processo de entrada de novatos no desenvolvimento do
kernel Linux durante o oferecimento da disciplina em 2024. Também planejamos
compilar as percepções dos alunos usando seus blog posts como fonte de
informação.

No momento de confecção da proposta do projeto, a ideia era restringir o escopo
ao desenvolvimento do kernel Linux, porém, como a disciplina demandou que os
alunos também contribuíssem em outras duas camadas do desenvolvimento do kernel
Linux - projetos que suportam os desenvolvedores e empacotamento de software no
contexto de distribuições Linux - preferimos expandir o escopo para ter uma
visão mais completa e contextualizada das observações dos docentes e discentes
da disciplina.

Como, nestas primeiras duas entregas, estamos focando em organizar os
dados/resultados advindos das diversas fontes de informação que o oferecimento
em 2024 da disciplina providenciou, acreditamos que é melhor analisarmos todos
eles, mesmo que alguns fujam do escopo delimitado inicialmente.

## 2) Observação dos monitores e do professor no oferecimento de 2024

No oferecimento de 2024 da disciplina, tivemos dois monitores ao decorrer de
toda a disciplina, que iremos nos referir como _Monitor 1_ e _Monitor 2_.
Importante notar que eu (David) fui um destes monitores.

As observações de ambos os monitores e do professor estão compiladas como
tópicos nos arquivos `entrega-2/observacao-monitores.txt`, e
`entrega-2/observacao-professor.txt`, respectivamente, que se encontram no
[**meu repositório de artefatos para a
disciplina**](https://github.com/davidbtadokoro/advanced-studies-softsys).

A forma que estes artefatos foram produzidos foi através de conversa direta com
os monitores e com o professor. Como eu que conduzi estas conversas, no meu caso
como monitor, eu apenas organizei minhas observações como tópicos. Sem alterar o
conteúdo das respostas que obtive, tentei ser o mais objetivo na escrita dos
artefatos supracitados.

Gostaria de saber se este formato de "coleta de dados" por conversa direta
influencia negativamente na produção do artigo e, se sim, como fazer para
organizar estas informações que não foram formalizadas (no sentido de não terem
sido registradas durante ou logo após a disciplina).

## 3) _Blogposts_ dos alunos no oferecimento de 2024

Ao decorrer da disciplina, os alunos tiveram que fazer _blogposts_ para cada
fase (na primeira fase, a maioria fez um post por tutorial, além do de
contribuição para o kernel Linux). Todos os links para os blogs de cada aluno
que terminaram a disciplina estão listados no arquivo
`entrega-2/lista-blogs.txt`.

Os nomes dos alunos foram ocultados desta lista, apesar de eles não estarem
anonimizados, pois, para a maioria deles, acessar o blog já indica a identidade
do aluno. Na confecção do artigo, a ideia é apenas utilizarmos as informações de
interesse (citações e perspectivas convergentes entre os _blogposts_) e remover
qualquer informação que identifique pessoalmente os alunos.

Assim como nas observações dos monitores e do professor, as observações dos
alunos advindas dos alunos foram compiladas no arquivo
`entrega-2/observacao-alunos-blogs.txt` em forma de tópicos.

Neste caso, como os _blogpost_ estão acessíveis e, portanto, os seus conteúdos
podem ser verificados, preferi adicionar citações diretas.

## 4) Conclusão

Pelos resultados obtidos do trabalho relacionado a esta entrega, podemos deduzir
com mais embasamento a tese central citada na entrega anterior de que o sucesso
no processo de entrada no ecossistema do kernel Linux depende fortemente de uma
orientação altamente especializada. Além disso, que uma exposição mais vertical
(_top-to-bottom_) de um ecossistema muito diverso e com muitas camadas de
desenvolvimento como o kernel Linux resulta em uma noção mais compreensível do
mesmo e de software livre no geral, além de agregar fortemente na formação dos
alunos como cientistas da computação. Ainda temos que decidir se limitamos o
escopo apenas ao desenvolvimento direto do kernel Linux e na entrada de novatos
no ecossistema, mas mesmo que decidamos seguir nesta direção, a inclusão das
outras fases da disciplina na contextualização da trajetória dos alunos será de
utilidade.
