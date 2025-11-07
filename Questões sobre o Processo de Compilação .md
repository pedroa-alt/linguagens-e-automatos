Questões sobre o Processo de Compilação em Java
1 Qual é a principal diferença entre o processo de compilação em Java e o de linguagens C++?
*Resposta*: "o código C++ é compilado diretamente para código de máquina nativo da plataforma, exigindo que ele seja recompilado para cada sistema operacional. Em contraste, o código Java é compilado para bytecode, um código intermediário que é depois interpretado e executado pela Máquina Virtual Java (JVM) em qualquer plataforma onde a JVM esteja instalada"
2 Explique o que acontece em cada uma das três fases de análise do compilador **javac**: Análise Léxica, Análise Sintática e Análise Semântica.
*Resposta*: "a fase de Análise Léxica converte o código-fonte em uma sequência de tokens; a Análise Sintática organiza esses tokens numa árvore sintática, verificando a estrutura gramatical do código; e a Análise Semântica valida o significado do código, como a declaração e o uso correto de variáveis e tipos de dados, para garantir que seja logicamente coerente"
3 O que é o bytecode e qual é a sua principal função no processo de construção do Java?
*Resposta*: "é um código intermediário gerado pela compilação de código-fonte Java, servindo como um formato de instruções não executáveis diretamente pelo hardware, mas compreensível pela Máquina Virtual Java (JVM)"
4 Qual é o papel da Máquina Virtual Java (JVM) na execução de um programa Java, e por que o arquivo ".class" não é executado diretamente pelo sistema operacional?
*Resposta*: "atua como um ambiente de execução que interpreta o bytecode (.class) e o traduz para instruções específicas da máquina, permitindo que o Java seja independente de plataforma"
5 O que é o compilador JIT e como ele melhorou o desempenho dos programas em Java?
*Resposta*: "melhora o desempenho de programas Java ao compilar o bytecode em código de máquina nativo e otimizado em tempo real, durante a execução"
6 Java é utilizada para criar aplicativos empresariais, web e móveis (Android)
*Resposta*: "Java é utilizada para criar aplicativos empresariais, web e móveis (Android)"
7 Nenhum processo de compilação de um código Java, como as linguagens formais são usadas nas fases de Análise Léxica e Análise Sintática?
*Resposta*: "as linguagens formais são utilizadas para definir e validar a estrutura do código-fonte"
8 O que é uma Máquina de Estado Finito (FSM) e como ela pode ser usada em Java?
*Resposta*: "é um modelo matemático e padrão de design de software que representa um sistema como um conjunto finito de estados, com o sistema passando de um estado para outro (transição) com base em entradas e eventos"
9 Como as linguagens formais se relacionam com os esquemas de validação de documentos, como os usados ​​para XML e JSON ?
*Resposta*: "A validação de documentos em relação a esses esquemas assegura a integridade e a precisão dos dados, o que é fundamental para a interoperabilidade entre diferentes sistemas"
10 De acordo com o texto, qual é a principal utilidade de ferramentas como o ANTLR no contexto de linguagens formais em Java?
*Resposta*: "A principal utilidade do ANTLR em Java, no contexto de linguagens formais, é a geração automática de analisadores léxicos (scanners ou tokenizadores), sintáticos (parsers), e árvores de análise sintática (ASTs) a partir de uma gramática definida pelo utilizador, permitindo criar programas que reconhecem, analisam e transformam dados de entrada de uma linguagem específica ou de domínios complexos"
