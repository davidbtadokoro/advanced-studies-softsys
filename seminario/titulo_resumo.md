# Título e Resumo do Seminário para Estudos Avançados em Sistemas de Software

Nome: David Tadokoro\
NUSP: 10300507\
Orientador: Paulo Meirelles\

<br>

### Data da apresentação: 08/05/25

### Título: Analyzing long-term maintenance releases of the Linux kernel

### Autores:

* Jesús Gonzalez-Barahona - Universidad Rey Juan Carlos (URJC)
* Gregorio Robles - Universidad Rey Juan Carlos (URJC)

### Resumo:

Este artigo analisou as atividades de manutenção nas versões LTS (_Long-Term
Support_) do kernel Linux, usadas amplamente em vários contextos, principalmente
pela indústria em ambientes de produção (computação em nuvem, servidores Web,
etc.). Apesar de serem consideradas "estáveis", essas versões recebem milhares
de commits por ano. A pesquisa minerou os repositórios git (chamadas neste
contexto de _kernel trees_) para entender: (1) a quantidade de _bugfixes_ e o
número de bugs que já existiam no início do ciclo de vida destas versões, (2) as
áreas do código mais afetadas, e (3) o tempo que as mudanças levam para serem
integradas às LTS. Os resultados mostram que cerca de 50% dos commits são
correções de bugs, áreas como drivers são as mais alteradas, e o tempo médio
para integrar mudanças é de dezenas de dias. Estes resultados são importantes
para caracterizar as atividades de manutenção destas versões estáveis, a carga
de trabalho que os mantenedores destas versões, e métricas e dados de interesse
para os _stakeholders_ destas soluções de software. 
