<h1>Página de Artista com HTML e CSS</h1>

<h2>Introdução</h2>
<p>Nesse projeto eu decidi usar minhas 3 semanas de estudos de <strong>HTML, CSS</strong> e <strong>FIGMA</strong> para refazer minha bio page de um site chamado <a target="_blank" href="https://bio.site/">Bio Site</a>,
decidi recriar a página, porém com meu próprio código e cores no designer, também com adição de algumas animações que eu decidi por em alguns elementos estáticos usando apenas CSS.</p>

<h2>Inicio</h2>
<p>para fazer o site eu comecei procurando pelas fontes usadas no site original, pra isso eu usei inspecionar nos textos e anotei o font-family de cada um com
  seus respectivos tamanhos em peso/weight e size, exportei as fontes no google fonts para meu CSS, entrei no site <a target="_blank" href="https://icons8.com/">Icons8</a> e baixei os icones do instagram, youtube
  e do spotify, todos em svg para não ter perda de qualidade em diferentes tamanhos, após isso comecei a estruturar minha página com <strong>HTML:5</strong>
no editor de código <strong>Visual Studio Code</strong>.</p>

<hr>

<h2>HTML:5</h2>
<h4>Estrutura</h4>
<p>Na estrutura comecei fazendo o básico de um index em estágio inicial, digitei "!" e expandi o código com o básico de uma página web,
mudei o html lang para Pt-br já que meu código seria em português brasil, os meta dados ficaram padronizados com charset="UTF-8" para não haver bugs nos caracteres
e o meta viewport para normalizar os pixels em diferentes telas, no title usei "Dias", meu nome de artista para ser algo mais direto em relação a página.
</p>

<h4>Conteúdo</h4>
<p>Já que minha página não haveria header e nem footer, decidi colocar apenas a tag "main" para segurar todo o conteúdo do meu site, dentro do "main" comecei a estrutura
  adicionando um parágrafo para a descrição "Artista" e h1 para o nome "Dias", após isso adicionei minha foto principal referente ao artista, e para isso usei a tag "figure"
para dar semântica ao conteúdo, e dentro de "figure" eu chamei minha imagem com "img src", depois usei a tag "nav" abaixo para criar três links com icons, dentro
de "nav" coloquei 3 tags "a" para criar âncoras com as midia e com target="blank" em todos os links do site para que eles abram em outra página, dentro das âncoras eu coloquei seus respectivos icones com "img", mas antes eu igualei o tamanho dos icones nos
códigos de cada imagem svg e mudei a cor deles para branco com o fill="white".</p>

<p>Partindo para os links em texto eu abri uma "div" com a mesma classe para cada âncora, dentro das âncora "a" eu coloquei uma div para todas pois eu precisaria usar pseudo-elementos com precisão em cada item para criar a numeração de 1 a 3, após isso eu apenas criei um "button" abaixo com uma âncora que leva para o site original da minha bio.</p>

<hr>

<h2>CSS</h2>
<h4>Reset</h4>
<p>Antes de começar a organização e estilização dos elementos do site eu resetei os estilos padrão, para isso usei asterisco "*" para mencionar o site inteiro e logo depois resetei a margin e o padding colocando eles com valor 0, assim eu posso dar meus próprios valores exatos de distância, também coloquei um box-sizing:border-box;
para que meus itens em caixa não acabem estourando para fora.</p>

<h4>Padrão</h4>
<p>Depois de resetar meus elementos eu comecei a criar um padrão para meus textos, assim eu mencionei "a","p","h1" até o "h6", coloquei color: white; para colorir os textos para branco e text-decoration: none; para remover os underlines dos meus links, também coloquei meu body com height em 100vh e meu width em 100% para não estourar o limite e acabar criando uma scrollbar abaixo/p>

<h4>Background Animado</h4>
<p>Minha ideia principal era deixar o site com um fundo preto igual ao original, porém eu decidi que queria usar alguma cor que eu gostasse e que combinasse com o estilo do site, então eu decidi usar roxo como estilo padrão da minha página, mas ai lembrei de alguns sites que usam fundos com cores animadas, mas eu não sabia como fazer :(, então eu procurei no youtube "Como fazer background animado CSS" :), após alguns tutoriais, eu procurei entender como que funcionava a animação do fundo, pois não queria apenas copiar e colar de um tutorial do youtube, assim eu poderia usar esse conhecimento em outros futuros projetos, então eu consegui, coloquei meu fundo animado, dentro do body eu coloquei um background em linar-gradient com 5 cores fazendo um fade do roxo escuro para o claro e depois voltando do claro para o escuro novamente, 1 2 3 2 1 por exemplo, para criar um ângulo de 45 graus no background eu usei o valor de 45deg antes de colocar as cores, assim agora meu fundo estava com o fade e o ângulo que eu queria,</p>
