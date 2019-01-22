<canvas id="custom" class="canvas" data-fragment-url="src/moon/moon.frag" data-textures="src/moon/moon.jpg" width="350px" height="350px"></canvas>

# O Livro dos Shaders
*por [Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/) e [Jen Lowe](http://jenlowe.net/)*

Este é um guia básico passo-a-passo sobre o complexo e abstrato universo dos Fragment Shaders.

<div class="header">
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B5FSVSHGEATCG" style="float: right;"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt=""></a>
</div>

## Conteúdo

* [Sobre o livro](00/)

* Começando
    * [O que é um shader?](01/)
    * [“Olá Mundo!”](02/)
    * [Uniforms](03/)
	* [Executando seu shader](04/)

* Desenhando com algorítimos
    * [Construíndo funções](05/)
    * [Cores](06/)
    * [Formas](07/)
    * [Matrizes](08/)
    * [Padrões](09/)

* Desenhos generativos
    * [Aleatório](10/)
    * [Ruído](11/)
    * [Ruído Celular](12/)
    * [Movimento browniano Fractal](13/)
    * Fractais

* Processamento de imagens
    * Texturas
    * Operações com imagens
    * Convolução do kernel
    * Filtros
    * Outros efeitos

* Simulação
    * Pingpong
    * Conway
    * Ondas
    * Aquarela
    * Reação de difusão

* Gráficos 3D
    * Luzes
    * Mapas-Normais
    * Bump-maps
    * Ray marching
    * Environmental-maps (esférico e cubo)
    * Reflexão e refração

* [Apêndice:](appendix/) Outras maneiras de usar o livro
	* [Como ver o livro offline?](appendix/00/)
	* [Como executar os exemplos em um Raspberry Pi?](appendix/01/)
	* [Como imprimir este livro?](appendix/02/)
    * [Como colaborar?](appendix/03/)
    * [Uma introdução para pessoas vindo de JS](appendix/04/) by [Nicolas Barradeau](http://www.barradeau.com/)

* [Galeria de exemplos](examples/)

* [Glossário](glossary/)

## Sobre os Autores

[Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/) (1982, Buenos Aires, Argentina) é uma artista e desenvolvedor baseado em Nova York. Ele explora espaços interstitiais entre orgânico e sintético, analógico e digital, individual e coletivo. Em seu trabalho ele usa código como uma linguagem de expressão com a intenção de desenvolver um melhor em conjunto.

Patricio estudou e pratica psicoterapia e terapia de arte expressiva. Ele possui Mestrado em Design & Tecnologia pela Parsons The New School, onde agora ensina. Atualmente ele trabalha como Engenheiro Gráfico na Mapzen fazendo ferramentas de mapeamento código-aberto.

<div class="header"> <a href="http://patriciogonzalezvivo.com/" target="_blank">WebSite</a> - <a href="https://twitter.com/patriciogv" target="_blank">Twitter</a> - <a href="https://github.com/patriciogonzalezvivo" target="_blank">GitHub</a> - <a href="https://vimeo.com/patriciogv" target="_blank">Vimeo</a> - <a href="https://www.flickr.com/photos/106950246@N06/" target="_blank"> Flickr</a></div>

[Jen Lowe](http://jenlowe.net/) é uma cientista de dados independente e uma comunicadora de dados na Datatelling, onde ela junta pessoas + números + palavras. Ela ensina na SVA's Design para Inovação Social, co-fundadora da School for Poetic Computation, ensinou Matemática para Artistas no NYU ITP, pesquisou no Spatial Information Design Lab na Universidade de Columbia, e contribuiu com ideias no escritório de Políticas em Ciências e Tecnologia da Casa Branca. Ela já se apresentou no SXSW e Eyeo. Seu trabalho já foi coberto pelo The New York Times e Fast Company. Sua pesquisa , textos, e palestras exploram as implicações e promessas da tecnologia e dados na sociedade. Ela possui B.S. em Matemática Aplicada e Mestrado em Information Science. Muitas vezes em oposição, ela está sempre do lado do amor.

<div class="header"> <a href="http://jenlowe.net/" target="_blank">WebSite</a> - <a href="https://twitter.com/datatelling" target="_blank">Twitter</a> - <a href="https://github.com/datatelling" target="_blank">GitHub</a></div>

## Agradecimentos

Obrigado [Scott Murray](http://alignedleft.com/) pela inspiração e conselhos.

Obrigado [Kenichi Yoneda (Kynd)](https://twitter.com/kyndinfo), [Nicolas Barradeau](https://twitter.com/nicoptere), [Karim Naaji](http://karim.naaji.fr/) pela contribuição com suporte, boas ideias e código.

Obrigado [Kenichi Yoneda (Kynd)](https://twitter.com/kyndinfo) e [Sawako](https://twitter.com/sawakohome) pela [Tradução Japonês (日本語訳)](?lan=jp)

Obrigado [Tong Li](https://www.facebook.com/tong.lee.9484) e [Yi Zhang](https://www.facebook.com/archer.zetta?pnref=story) pela [Tradução em Chinês (中文版)](?lan=ch)

Obrigado [Jae Hyun Yoo](https://www.facebook.com/fkkcloud) pela [Tradução Koreano (한국어)](?lan=kr)

Obrigado [Nahuel Coppero (Necsoft)](http://hinecsoft.com/) pela [Tradução Espanhol (español)](?lan=es)

Obrigado [Nicolas Barradeau](https://twitter.com/nicoptere) e [Karim Naaji](http://karim.naaji.fr/) pela [tradução Francês (français)](?lan=fr)

Obrigado [Andrea Rovescalli](https://www.earove.info) pela [tradução Italiano (italiano)](?lan=it)

Obrigado [Michael Tischer](http://www.mitinet.de) pela [tradução Alemão (deutsch)](?lan=de)

Obrigado [Sergey Karchevsky](https://www.facebook.com/sergey.karchevsky.3) pela [tradução Russo (russian)](?lan=ru)

Obrigado a todos que acreditaram neste projeto e [contribuíram com correções](https://github.com/patriciogonzalezvivo/thebookofshaders/graphs/contributors) ou doações.

## Receba novos capítulos

Assine o newsletter ou [siga no Twitter](https://twitter.com/bookofshaders)

 <form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/thebookofshaders" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/thebookofshaders', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><a href="https://tinyletter.com/thebookofshaders"><p><label for="tlemail">Enter your email address</label></p></a><p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Subscribe" /><p><a href="https://tinyletter.com" target="_blank"></a></p></form>
