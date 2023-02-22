<h1>Página de Artista com HTML e CSS</h1>

<h2>Introdução</h2>
<p>Nesse projeto eu decidi usar minhas 3 semanas de estudos de <strong>HTML, CSS</strong> e <strong>FIGMA</strong> para refazer minha bio page de um site chamado <a target="_blank" href="https://bio.site/">Bio Site</a>,
decidi recriar a página, porém com meu próprio código e cores no designer, também com adição de algumas animações que eu decidi por em alguns elementos estáticos usando apenas CSS.</p>

<h2>Inicio</h2>
<p>para fazer o site eu comecei procurando pelas fontes usadas no site original, pra isso eu usei inspecionar nos textos e anotei o font-family de cada um com
  seus respectivos tamanhos em peso/weight e size, exportei as fontes no google fonts para meu CSS, entrei no site <a target="_blank" href="https://icons8.com/">Icons8</a> e baixei os icones do instagram, youtube
  e do spotify, todos em svg para não ter perda de qualidade em diferentes tamanhos, após isso comecei a estruturar minha página com <strong>HTML:5</strong>
no editor de código <strong>Visual Studio Code</strong>.</p>

<h2>HTML:5</h2>
<h4>Estrutura</h4>
<p>Na estrutura comecei fazendo o básico de um index em estágio inicial, digitei "!" e expandi o código com o básico de uma página web,
mudei o html lang para Pt-br já que meu código seria em português brasil, os meta dados ficaram padronizados com charset="UTF-8" para não haver bugs nos caracteres
e o meta viewport para normalizar os pixels em diferentes telas, no title usei "Dias", meu nome de artista para ser algo mais direto em relação a página.
</p>

<h4>Conteúdo</h4>
<p>Já que minha página não haveria header e nem footer, decidi colocar apenas a tag "main" para segurar todo o conteúdo do meu site, dentro do "main" comecei a estrutura
  adicionando um parágrafo para a descrição "Artista" e h1 para o nome "Dias", após isso adicionei minha foto principal referente ao artista, e para isso usei a tag "figure"
para dar semântica ao conteúdo, e dentro de "figure" eu chamei minha imagem com "img src", depois usei a tag "nav" para criar três links com icons, dentro
de "nav" coloquei 3 tags "a" para criar âncoras com as midia, e dentro das âncoras eu coloquei seus respectivos icones com "img", mas antes eu igualei o tamanho dos icones nos
códigos de cada imagem svg e mudei a cor deles para branco com o fill="white"</p>
