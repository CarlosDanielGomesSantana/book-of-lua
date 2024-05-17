# Introdução

> Essa introdução é encontrado em Português no site [aqui](https://lua.org/portugues.html) 

## O que é Lua?

Lua é uma linguagem de programação poderosa, eficiente e leve, projetada para estender aplicações. Ela permite programação procedural, programação orientada a objetos, programação funcional, programação orientada a dados e descrição de dados.

Lua combina sintaxe procedural simples com poderosas construções para descrição de dados baseadas em tabelas associativas e semântica extensível. Lua é tipada dinamicamente, é executada via interpretação de bytecodes para uma máquina virtual baseada em registradores, e tem gerenciamento automático de memória com coleta de lixo incremental. Essas características fazem de Lua uma linguagem ideal para configuração, automação (scripting) e prototipagem rápida.

## Quais as origens de Lua?

Lua é inteiramente projetada, implementada e desenvolvida no Brasil, por uma equipe na PUC-Rio (Pontifícia Universidade Católica do Rio de Janeiro). Lua nasceu e cresceu no Tecgraf, o então Grupo de Tecnologia em Computação Gráfica da PUC-Rio. Atualmente, Lua é desenvolvida no laboratório LabLua do Departamento de Informática da PUC-Rio.

## Por que escolher Lua?

* ### Lua é linguagem estabelecida e robusta

    Lua é usada em muitas aplicações industriais (e.g., Adobe's Photoshop Lightroom), com ênfase em sistemas embutidos (e.g., o middleware Ginga para TV digital) e jogos (e.g., World of Warcraft e Angry Birds). Lua é atualmente a linguagem de script mais usada em jogos. Lua tem um sólido manual de referência e existem vários livros sobre a linguagem. Várias versões de Lua foram lançadas e usadas em aplicações reais desde a sua criação em 1993.

* ### Lua é rápida

    Lua tem uma merecida reputação de ótimo desempenho. Outras linguagens de script aspiram ser "tão rápidas quanto Lua". Vários benchmarks mostram Lua como a linguagem mais rápida dentre as linguagens de script interpretadas. Lua é rápida não só em programas específicos para benchmarks, mas no dia-a-dia também. Porções substanciais de aplicações grandes são escritas em Lua.
    
    Se você precisar de ainda mais velocidade, experimente LuaJIT, uma implementação independente usando um compilador just-in-time.

* ### Lua é portátil

    Lua é distribuída via um pequeno pacote e compila sem modificações em todas as plataformas que têm um compilador C padrão. Lua roda em todos os tipos de Unix e Windows, e também em dispositivos móveis (usando Android, iOS, BREW, Symbian, Windows Phone), em microprocessadores embutidos (como ARM e Rabbit, para aplicações como Lego MindStorms), e até mainframes IBM.

* ### Lua é embutível

    Lua é uma engine rápida e pequena que você pode facilmente embutir na sua aplicação. Lua tem uma API simples e bem documentada que permite uma integração forte com código escrito em outras linguagens. É simples estender Lua com bibliotecas escritas em outras linguagens. Também é simples estender programas escritos em outras linguagens com Lua. Lua é usada para estender programas escritos não só em C e C++, mas também em Java, C#, Smalltalk, Fortran, Ada, Erlang, e mesmo outras linguagens de script, como Perl and Ruby.

* ### Lua é poderosa (e simples)

    Um conceito fundamental no projeto de Lua é fornecer meta-mecanismos para a implementação de construções, em vez de fornecer uma multidão de construções diretamente na linguagem. Por exemplo, embora Lua não seja uma linguagem puramente orientada a objetos, ela fornece meta-mecanismos para a implementação de classes e herança. Os meta-mecanismos de Lua trazem uma economia de conceitos e mantêm a linguagem pequena, ao mesmo tempo que permitem que a semântica seja estendida de maneiras não convencionais.

* ### Lua é pequena

    Incluir Lua numa aplicação não aumenta quase nada o seu tamanho. O pacote de Lua 5.4.6, contendo o código fonte e a documentação, ocupa 355K comprimido e 1.4M descompactado. O fonte contém cerca de 30000 linhas de C. No Linux de 64 bits, o interpretador Lua contendo todas as bibliotecas padrões de Lua ocupa 282K e a biblioteca Lua ocupa 470K.

* ### Lua é livre

    Lua é software livre de código aberto, distribuída sob uma licença muito liberal (a conhecida licença MIT). Lua pode ser usada para quaisquer propósitos, incluindo propósitos comerciais, sem qualquer custo ou burocracia. Basta fazer um download e usá-la.

* ### Lua tem importância global

    Lua é a única linguagem de programação com impacto mundial desenvolvida fora do primeiro mundo.

    O projeto e a evolução de Lua foram apresentados em 2007 na HOPL III, a 3a Conferência da ACM sobre a História das Linguagens de Programação. Essa conferência ocorre a cada 15 anos (em 1978, 1993, 2007, 2021) e apresenta linguagens de impacto. A escolha de Lua para a HOPL III é um importante reconhecimento do seu impacto mundial.
    
    Lua ganhou o Front Line Award 2011 da Game Developers Magazine na categoria ferramentas de programação.
    Em 2017, Lua foi exibida na exposição Inovanças - Criações à Brasileira, no Museu do Amanhã no Rio de Janeiro, como uma das "criações pensadas e 
    desenvolvidas por brasileiros que transformam vidas no país e no mundo". Veja o video de abertura e leia o catálogo. Veja o video sobre Lua.
    
    Em 2022, Lua recebeu a Medalha Pedro Ernesto, a comenda máxima da cidade do Rio Janeiro.
