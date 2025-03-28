# Relatório da Entrega 1 de Estudos Avançados em Sistemas de Software (27/03/2025)

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

Nesta primeira entrega, o objetivo era organizar o feedback geral coletado
através de um questionário da
turma de 2024.

## 2) Feedback do questionário sobre experiência dos alunos de 2024

Ao final da disciplina, foi pedido aos alunos que preenchessem um questionário
na instância do [LimeSurvey](https://en.wikipedia.org/wiki/LimeSurvey). A
plataforma oferece várias funcionalidades.

No entanto, um trabalho muito manual que foi necessário ser feito foi a limpeza
das rodadas piloto e da organização das respostas em tópicos relacionados (por
algum motivo, a plataforma havia misturado os tópicos dos questionários). O
resultado da limpeza inicial dos dados foi o arquivo
`entrega-1/resultados-questionario-2024.pdf` que se encontra no
[**meu repositório de artefatos para a disciplina**](https://github.com/davidbtadokoro/advanced-studies-softsys).
Neste diretório encontram-se outros artefatos como o arquivo Markdown que gerou
este relatório e alguns gráficos (ainda estamos identificando quais dados
visualizar e de que forma).

Utilizando este arquivo pudemos observar alguns resultados muito interessantes
que são descritos na seção a seguir.

Ao todo, foram obtidas 20 respostas.

## 3) Resultados notáveis do questionário

O questionário contava com 43 perguntas separadas em grupos, então há muito
material que podemos utilizar para o artigo. A seguir, há uma sequência de
resultados interessantes do questionário.

#### Demográfico\

70% dos respondentes eram alunos de graduação e todos estavam pelo menos em seu
terceiro ano, 20% dos alunos eram de pós-graduação, enquanto 10% eram alunos
especiais. Além disso, 65% dos respondentes afirmaram terem 3 ou mais anos de
experiência com programação de forma não profissional e apenas 25% haviam 3 ou
mais anos de experiência com programação de forma profissional.

#### Importância do Git como base\

85% dos respondentes disseram que tinham alguma experiência (50%) ou muita
experiência (35%) com o uso de Git localmente. Além disso, 70% dos respondentes
tinham alguma experiência (55%) ou muita experiência (15%) com plataformas web
de hospedagem de repositório de códigos como GitHub e GitLab, mas apenas 55% dos
respondentes disseram que tinham alguma experiência (35%) ou muita experiência
(20%) com fluxos de trabalho que de *pull requests* nestas plataformas
(Pull-Requets do GitHub, Merge-Requests do GitLab, etc.).

Por outro lado, 80% dos respondentes não haviam tido contato com fluxos de
trabalho que utilizam email como meio de transmissão de contribuições, a qual é
a forma hegemônica utilizada no projeto do kernel Linux.

Dos 20 respondentes do questionário, 5 (25%) concordaram que a processo de
mentoria no kernel Linux e contribuição para projetos de software livre melhorou
as habilidades de Git, 13 (65%) concordaram fortemente, e 2 (10%) não
responderam.

Ao final da disciplina, 17 respondentes (85%) afirmaram que habilidades com Git
foram dentre as mais importantes para o sucesso no curso.

#### Bom conhecimento de software livre mas pouco contato\

70% dos respondentes afirmaram serem familiares com o conceito de software
livre, mas 25% afirmaram já terem contribuído para um projeto de software livre.
Por outro lado, 75% dos respondentes concordaram (45%) ou concordaram fortemente
(25%) que utilizariam a experiência de contribuir para algum projeto de software
livre.

Além disso, 75% dos respondentes concordaram (30%) ou concordaram fortemente
(45%) que se sentem confortáveis em contribuir para qualquer projeto de software
livre ao final da disciplina.

#### Contato com Linux como usuário e desenvolvedor\

Antes da disciplina, 70% dos respondentes tinham ao menos 1 ano de experiência
com Linux como usuário, mas apenas 25% haviam tido algum tipo de contato com
desenvolvimento Linux (não necessariamente de enviar patches para algum
sub-projeto Linux).

Ao final da disciplina, 65% dos respondentes concordaram (45%) ou concordaram
fortemente (20%) que a experiência na disciplina tornou eles aptos a
contribuírem para algum projeto Linux no futuro. No entanto, apenas 40% ao menos
concordaram que considera contribuir para algum projeto Linux, seja como
voluntário ou profissionalmente.

#### Importância da mentoria com acompanhamento próximo e workshops presenciais\

90% dos respondentes concordaram (10%) ou concordaram fortemente (80%) que a
orientação dos monitores era útil para se completar as tarefas, enquanto 85%
concordaram (15%) ou concordaram fortemente (70%) que ela foi crítica. 

80% dos respondentes afirmaram que os workshops presenciais foram um dos pontos
fortes da disciplina e 85% disseram o mesmo em relação ao suporte dos monitores.

## 4) Conclusão

Ainda é necessário decidir em qual direção queremos seguir em relação à escrita
do artigo, porém, com a execução das atividades relacionadas a esta entrega,
estamos consideravelmente seguros sobre a tese central de que o sucesso no
processo de entrada no ecossistema do kernel Linux depende fortemente de uma
orientação altamente especializada. Logicamente, falta considerar outras as
fontes de informações, mais especificamente, as observações dos monitores e do
professor, os *blog posts* dos alunos e os dados referentes a edição de 2025 da
disciplina para entendermos com melhor robustez este fenômeno de introdução de
novatos ao ecossistema do kernel Linux.
