# Introdução

<canvas id="custom" class="canvas" data-fragment-url="cmyk-halftone.frag" data-textures="vangogh.jpg" width="700px" height="320px"></canvas>

As imagens acima foram concebidas de diferente maneiras. A primeira foi feita pelas mãos de Van Gogh aplicando camada por camada de tinta. Ele gastou horas para isso. A segunda foi produzida em segundos pela combinação de quatro matrizes de pixels: uma para a cor ciano, magenta, amarelo e preto. A principal diferença é que a segunda imagem é produzida de uma maneira não sequencial (isso é, não passo-a-passo mas toda de uma só vez ).

Este livro é sobre uma técnica revolucionária, *fragment shaders*, que esta levando a geração digital de imagens a outro patamar. Você pode pensar isso como o equivalente a imprensa de Gutenberg mas para gráficos.

![Imprensa por Gutenberg's](gutenpress.jpg)

Fragment shaders possibilitam controle total sobre os pixels renderizados na tela, a uma super velocidade.
Por isso eles são utilizados em diversos casos, de filtros em vídeos no telefone celular a incríveis video games 3D.

![Journey por That Game Company](journey.jpg)

Nos próximos capítulos você descobrirá como esta técnica é incrivelmente rápida e poderosa, e como aplicar para seu trabalho profissional e pessoal.

## Para que este livro se aplica?

Este livro foi escrito para programadores criativos, desenvolvedores e engenheiros que tem experiência programando, conhecimentos básicos de álgebra linear e trigonometria, e para aqueles que querem levar seus trabalhos a um novo nível de qualidade gráfica.(Se você gostaria de aprender a programar, eu recomendo fortemente começar com [Processing](https://processing.org/) e voltar para cá quando estiver confortável com o básico.)

Este livro te ensinará como usar e integrar shaders no seus projetos, melhorando sua performance e qualidade gráfica. Você será capaz de aplicar o que aprender aqui em qualquer ambiente que use OpenGL, OpenGL ES ou WebGL, já que GLSL (OpenGL Shading Language) compila e executa em diversas plataformas. Ou seja, você será capaz de aplicar e usar seu conhecimento com sketches do [Processing](https://processing.org/), aplicações [openFrameworks](http://openframeworks.cc/), instalações interativas com [Cinder](http://libcinder.org/), websites ou iOS/Android games com [Three.js](http://threejs.org/).

## O que este livre cobre?

Este livro focará no uso de pixel shaders GLSL. Primeiramente nós vamos definir o que são shaders; então vamos aprender a como gerar formas procedurais, padrões, texturas e animações. Você aprenderá os fundamentos da linguagem de shaders e aplicar para cenários para úteis como, processamento de imagens (operações com imagens, convolução de matrizes, blurs, filtros de cores, tabelas lookup e outros efeitos) e simulações (Conway jogo da vida, reação de difusão Gray-Scott, ondas de água, efeitos aquarela, células Voronoi, etc.). No final do livro, vamos ver um conjunto de técnicas avançadas baseadas em Ray Marching.

*Em cada capítulo, há exemplos interativos para você testar.* Quando você precisar alterar o código, você notará mudanças imediatas na tela. Os conceitos pode ser abstratos e confusos, desta maneira os exemplos interativos são essenciais para ajudar no aprendizado do material. O quão rápido você colocar os conceitos em prática mais fácil vai ser o processo de aprendizado.

O que este livro não cobre:

* Este *não é* um livro sobre openGL ou webGL. OpenGL/webGL é um assunto muito maior que GLSL ou fragment shaders. para aprender mais sobre openGL/webGL eu recomendo olhar:  [OpenGL Introduction](https://open.gl/introduction), [the 8th edition of the OpenGL Programming Guide](http://www.amazon.com/OpenGL-Programming-Guide-Official-Learning/dp/0321773039/ref=sr_1_1?s=books&ie=UTF8&qid=1424007417&sr=1-1&keywords=open+gl+programming+guide) (também conhecido como o livro vermelho) ou [WebGL: Up and Running](http://www.amazon.com/WebGL-Up-Running-Tony-Parisi/dp/144932357X/ref=sr_1_4?s=books&ie=UTF8&qid=1425147254&sr=1-4&keywords=webgl)

* Este *não é* um livro de matemática. Entretanto, nós cobriremos alguns algoritmos e técnicas que dependem do entendimento de álgebra e trigonometria, nós não explicaremos eles em detalhe. Para mais questões sobre matemática eu recomendo manter os seguintes livros por perto: [3rd Edition of Mathematics for 3D Game Programming and computer Graphics](http://www.amazon.com/Mathematics-Programming-Computer-Graphics-Third/dp/1435458869/ref=sr_1_1?ie=UTF8&qid=1424007839&sr=8-1&keywords=mathematics+for+games) or [2nd Edition of Essential Mathematics for Games and Interactive Applications](http://www.amazon.com/Essential-Mathematics-Games-Interactive-Applications/dp/0123742978/ref=sr_1_1?ie=UTF8&qid=1424007889&sr=8-1&keywords=essentials+mathematics+for+developers).

## O que você precisa para começar?

Nada demais! Se você possui um browser moderno com capacidade para WebGL (como Chrome, Firefox ou Safari) e uma conexão com a internet, clique no botão "Próximo" no final desta página para começar.

De maneira alternativa, baseado no que você tem ou o que você precisa deste livro:

- [Como fazer uma versão off-line do livre](https://thebookofshaders.com/appendix/00/)

- [Como rodar exemplos em um Raspberry Pi sem um browser](https://thebookofshaders.com/appendix/01/)

- [Fazer um PDF do livro para imprimir](https://thebookofshaders.com/appendix/02/)

- Cheque o [repositório GitHub](https://github.com/patriciogonzalezvivo/thebookofshaders) deste livro para ajuda com resolvendo problemas ou compartilhar o código fonte.
