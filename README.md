Aplicação Multi-Layout com Zend Framework 2
=======================

Sobre este exemplo
------------
Continuando na toada de front-end, continuarei falando de uma tecnologia que integrada ao Zend Framework 2 traz uma gama de benefícios imensuráveis, 
que é o Twig. Se você nunca trabalhou ou ouviu falar dele, clique aqui. Twig é uma tecnologia baseada no PHP, mas, 
com uma proposta diferente: modelar os templates da aplicação. 

Sabemos que ao construir uma aplicação PHP, teremos arquivos .php, .phtml ou qualquer extensão que seja, 
com instruções PHP misturadas com as tags HTML, porém, se formos pensar do ponto de vista conceitual de front-end e templates, 
é algo confuso e de difícil manutenção, porque, o código PHP misturado ao HTML acaba poluindo a legibilidade do código, 
por todas as questões de sintaxes de uma linguagem voltada para o back-end. Além de ter uma sintaxe mais amigável e legível aos templates, 
o Twig traz muitos outros benefícios. Um dos principais para mim é o ganho de desempenho de renderização do código HTML. 
Mas, aí você se pergunta: embutindo mais uma tecnologia na aplicação que ainda virará um código PHP para depois ser gerado 
um HTML só pode fazer a aplicação ficar mais lenta, pra quê isso? É desnecessário!

Pois, eu afirmo com certeza que não!

Até já vi em alguns fóruns por aí, especialmente no Google Groups, de pessoas falando que o Twig atrapalha a aplicação. 
Um dia vi que uma pessoa perguntou qual a importância do Twig, outro falou: apenas usa-lo, então, uma outra pessoa responde: 
Você está acrescentando mais uma tecnologia na aplicação que vai atrasar o tempo de execução do código, 
já que do Twig ainda terá que ser gerado um código PHP e depois o HTML, então, é desnecessário, não vale a pena.

Diante do que falei no final do parágrafo acima, é preciso, no mínimo, ler um pouco da documentação da biblioteca, 
para se ter o mínimo de conhecimento ao se falar sobre alguma coisa... para não sair falando qualquer coisa, 
é preciso primeiro conhecer... O Twig, internamente, gera classes com código de nossos templates fazendo uma série de otimizações,
desde a reduções de espaços desnecessários, redução de código, etc, portanto, teremos um ganho de performance comparado a se não estivéssemos usando o Twig.

Neste tutorial usaremos a biblioteca de terceiro, chamada ZfcTwig, que faz a integração necessária para usarmos o Twig com Zend Framework 2.
[Veja o link do tutorial](http://www.schoolofnet.com/2015/03/como-usar-twig-com-zend-framework-2/)