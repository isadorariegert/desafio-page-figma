# Desafio 


### Algumas Explicacoes sobre a Page:

- A pagina foi criada segundo um layout disponivel no FIGMA enviado pela Cinetica.Lab:
![](https://www.figma.com/proto/Jn5bqYri24WahexA6Kgske/teste?node-id=1%3A2&scaling=min-zoom) 
- A partir dele, repliquei o conteudo seguindo as medidas propostas no FIGMA para um mediascreen de 1440px (width do background do layout enviado).
- Para manter a melhor performance, disponibilizei a img inicial por src'url', porem tambem salvei e dimensionei a imagem disponibilizada no FIGMA nos tamanhos compativeis com cada screen usada (manti o codigo comentado apenas como segunda opcao).
- Para os icones "no-profile-picture", salvei o arquivo em SVG, e a imagem Inicial converti para webP, para melhor performance.

### Tecnologias usadas:

- HTML
- CSS
- Bootstrap

### Desenvolvimento:

- Apesar do layout proposto ser enviado numa scren 1440, apliquei o estilo seguindo MobileFirst por se tratar de uma pratica comum da Cinetica;
- Criei a estilizacao CSS para Mobile (min-width:425px), priorizando a definicao de tamanho por VW, para manter ajuste de tela.
- Adicionei @mediaScreen compativeis com min-width: 768px, 1024px, 1440px, alem de breakpoints que julguei necessario em 580px e 1600px;
- Introduzi os breakpoins/media queries no decorrer do codigo CSS, pois essa e' a forma que eu considero mais facil para leitura/manutencao;
- Nao minifiquei o CSS pois imaginei que seria um dificultador durante a avaliacao do codigo;
- Adicionei eventos apenas atraves do Hover (CSS), pois pela simplicidade da page, acreditei ser desnecessario inserir eventos JS.


### Highlights:

- Tentei ao máximo utilizar uma boa semântica no código, tanto para SEO quanto para acessibilidade;
- Para a utilização de leitores de telas, o código esta' na ordem que ele tem que ser lido;
- Alguns pontos de acessibilidade ficaram falhos pois segundo audit, o background e a fontcolor nao tiveram contraste suficiente, porem acreditei ser importante seguir os padroes de layout encaminhados pela empresa;
- Tambem pensei que a usabilidade da pagina para telas acima de 780px poderia ser melhorada separando em diferentes sections visiveis durante a rolagem, porem seria necessario mudar o padrao dos formatos enviados, entao preferi manter segundo o layout proposto.

![](https://raw.githubusercontent.com/isadorariegert/desafio-page-figma/master/img/audit.png)

>  <3
>  Agradeco desde ja a oportunidade e a atencao.
>  <3

![](http://mochimochiland.com/images/knittinggnome600.gif)
