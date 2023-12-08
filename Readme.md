# PRIMEIROS PASSOS EM HTML E CSS
Olá, esse são meus primeiros passos para aprender CSS e HTML. Minhas fontes de estudo foram a playlit do [curso em video](https://www.youtube.com/watch?v=Ejkb_YpuHWs&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n) e com apoio do tecghuide. 

## EX001:
Foi meu primeiro contato com HTML. Utilizo as estruturas básicas (!) e algumas tags como title, p e h1.

## EX002:
O segundo passo foi explorando os parágrafos e as quebras de linhas ('p', '/p', 'br').

Logo em seguida aprendi a utilizar símbolos especiais e emojis (estrtura é &#xcódigo; Os códigos podem ser achados no site [emojipedia](https://emojipedia.org/zany-face#technical)).

## EX003:
O terceiro passo é a tag 'IMG' (imagens), questões importantes precisam ser analisadas, já que direitos autorais são de suma importância. Além do mais, o tamanho da imagem pode influenciar no desempenho do seu site.

Aqui eu demosntro dois formatos para adiconar a imagem. Um ponto importante é a aquestão da estrutura da tag, então fique atento ('src'-link | 'alt'-descrição para pessoas com deficiência visual).

## EX004:
Nesse quarto passo, aprendi a colocar o 'fivicon'(link rel="shortcut icon" href="" type="image/x-icon"), que nada mais é o ícone que fica ao lado do title (ou seja, ao lado do nome que fica na aba do navegador).

Para isso, usei dois sites -> [iconarchive](https://www.iconarchive.com/show/gartoon-apps-icons-by-gartoon-team/amarok-wolf-icon.html#google_vignette) e [favicon](https://favicon.io/).

## EX005:
Seguindo com o quinto passo, aprofundo na questão da hierarquia dos títulos. Nessa parte, entendo os níveis h1 até h6. Utilizo como base o súmario do livro "Rápido e Devagar Duas formas de pensar" de Daniel Kahneman.

Outro ponto importante é que com CSS podemos modificar esses títulos, como cores, tamanhos e etc. 

## Atenção:
Tomar cuidado com a semântica e a forma, semântica é o jeito certo de se escrever (sentido) e forma é uma parte que fica com CSS (não leva o sentido), ou seja, muitas tags que eram usadas em versões passadas de HTML já não são aceitas mais. Por isso, sempre ficar de olho para não utilizar tags obsoletas. O HTML5 é conhecido como HTML semântico.

## EX006:
Seguindo a questão da semântica, aprendo a utilizar tags para deixar em negrito e itálico do jeito certo. O ponto é que existes tags como 'i' e 'b' que realizam a mesma função, mas elas são formas, não dão importância ao significado, sendo assim deveriam ficar por parte do CSS. 

Por outro lado, as tags 'STRONG' e 'EM' são semânticas. Sendo assim, são mais aceitável do que as outras citadas.

## EX007:
O próximo passo é utilizar a tag 'MARK' de marcador (é semântico, já que você está marcando aquela palavra). O ponto importânte é que para mudar a cor do marcador é necessário CSS, já que é forma. Sendo assim, entrando em CSS podemos adicionar no cabeçalho HEAD um seletor STYLE para 'MARK' com background-color e escolher a cor que desejar (todos os marcadores ficaram com essa cor, para especificar tem que colocar a palavra dentro da tag 'MARK').

Segundo passo é deixar o texto menor, para isso, usamos tag SMALL. Para deixar grande é visto como não semântico, então seria parte de CSS. 

Terceiro passo é as tags para texto deletado e inserido ('DEL' / 'INS'). E para sobrescrito como a formula x20+3, onde queremos que o x seja elevado ao 20 ('SUP') e subscrito como a dormula H20, onde queremos que o 2 seja relativamente menor ('SUB'). 

## EX008:
No oitavo passo, usamos primeiramente a tag 'CODE' muito boa para representar códigos (fonte monoespaçada). Um ponto importânte é que essa tag não leva em considerações os espaços, linhas e tabulações. O que gera uma representação não muito habitual de código, para isso emvelopamos a tag 'CODE' por outra tag 'PRE'. 

Dando continuidade, para fazer citações, é melhor usar a tag 'q' para colocar aspas, visto que estamos dando sentido àquela frase, ou seja, é de fato uma citação e não uma afirmação direta. Nesse caso, estamos entrando na discussão semântica da coisa. Outra questão é a tag 'blockquote' para citações mais complexas, como frases de autores, filmes e livros. Além da tag, é bom adicionar um atributo 'cite' para colar o link de onde você pegou a citação. Isso não aparecerá na tela, mas o Google ou seu navegador utilizará para mecanismos de busca.

Para finalizar este EX008, utilizamos a tag de abreviação 'abbr' acompanhada do atributo 'title'. Esse elemento faz com que, ao passar o mouse sobre a palavra, seja exibido o significado daquela abreviação. É importante observar que visualmente pode não ser esteticamente agradável, mas podemos aprimorar isso utilizando CSS.

## EX009:
O nono passo são as listas, muito importantes. Existem as listas ordenadas, não ordenadas e de definição. Começando pela ordenada, podemos usar a tag 'ol', e dentro dela, a tag 'li' para organizar a lista. Um ponto importante é que um atributo da tag 'ol' é 'type=""', onde podemos escolher a formatação (se é em letras maiúsculas ou minúsculas, elementos romanos ou números).

A segunda forma de listas é a não ordenada, sua diferença é que a ordem não importa e usamos a tag 'ul'. Aqui podemos variar de pontinhos preto, quadrados ou circulos abertos. Em relação a estrutura é parecida com a tag 'li'.

Podemos ir além e adicionar listas ordenadas dentro de outras listas ordenadas, assim como listas não ordenadas dentro de listas ordenadas, podendo modificar os tipos e o ponto de início conforme necessário. A última forma é a lista de definição, onde usamos a tag 'dl', e dentro dela, 'dt' para termos e 'dd' para suas definições (veja o exemplo para ter um entendimento melhor).

## EX010:
Neste décimo passo, abordamos os links, uma das partes mais cruciais, uma vez que a navegação na web é fundamentada nesses elementos. Inicialmente, utilizamos links externos de duas maneiras; em ambas as abordagens, empregamos a tag 'a' com o atributo 'href=""' para incorporar a mensagem e a URL do site externo. Vale ressaltar que, ao clicarmos no link, a página web vinculada substituirá a nossa, ou seja, faremos a transição para fora dela. Se desejarmos abrir uma nova guia sem fechar a nossa, é necessário usar um atributo adicional, sendo 'target="_blank"' e 'rel="noopener"'.

Ao acessarmos links internos, criamos um novo arquivo denominado "pagina002". O processo é semelhante, onde adicionamos as tags, com a distinção de que não necessitamos da URL. No atributo "rel", utilizamos "next" para auxiliar os motores de busca a compreenderem que estamos estabelecendo uma estrutura de relação entre as páginas do site. Ao ingressarmos na página dois, temos a opção de incluir um link para retornar à página principal. Além disso, empregamos o atributo "rel" com "prev" para indicar ao mecanismo de busca que é possível retornar à página anterior.

### Atenção: 
Existe o atributo "rel" com o valor "nofollow" (está no primeiro link do arquivo index.html para ver exemplo), que é utilizado para desencorajar ou evitar a indexação de links para determinadas páginas. Essa prática é frequentemente adotada em links de comentários de blogs ou fóruns, especialmente quando os administradores desejam evitar que spammers se aproveitem dos links deixados nos comentários para aprimorar o ranking de seus sites nos resultados de pesquisa.

Se criarmos uma página dentro de uma pasta que está dentro da nossa pasta ex010, para acessá-la, é necessário seguir o caminho correto, informando o nome da pasta e, em seguida, o do arquivo. Para retornar, podemos utilizar uma abordagem semelhante ao estilo Linux, usando '../index.html' para voltar à página principal.

Para finalizar, utilizamos o link para download. Criamos uma nova pasta dentro da pasta ex010 e adicionamos um arquivo PDF nela. No arquivo principal "index", adicionamos a tag 'a', especificando o link da pasta e do arquivo PDF. Adicionalmente, incluímos o atributo download="nome do arquivo". Dessa forma, ao acessarmos a página web e clicarmos no link, o arquivo será baixado automaticamente.

### OBS: 
Podemos compactar o arquivo em pdf zimapando ele. Aém do mais, no atributo download usamos o '.pdf' essas aplicações podem  variar de acordo com o tipo de formatação do aquivo, para isso é só acessar o site [MediaTypes](https://www.iana.org/assignments/media-types/media-types.xhtml) e conferir.

## Desafio001: 
O ponto de partida era criar uma página web do meu perfil (não me usei como base, mas sim um personagem de um anime, então não considero as informações relevantes, é apenas um exemplo). Inicialmente, deveria começar com um título ("Minha Rede Social") e um subtítulo ("Quem sou eu?"). Em seguida, precisava adicionar uma imagem arredondada do personagem, o que se mostrou o ponto mais difícil. Tive que usar o [gimp](https://www.gimp.org/downloads/) para diminuir e arredondar a imagem.

Após isso, elaborei uma breve descrição do personagem e criei um subtítulo ("Como falar comigo?"), adicionando links que direcionam para meu LinkedIn, GitHub, um vídeo aleatório do personagem no YouTube e o Instagram de uma fã (todos com links e imagens associadas).

## EX011: 
Entramos nas imagens dinâmicas, que são importantes porque, dependendo do dispositivo que seu cliente está usando, elas se adaptarão. Isso precisa ser levado em consideração, uma vez que os usuários não gostam de ajustar a imagem; portanto, ela deve se adaptar ao tamanho automaticamente.

Para isso, utilizando o GIMP, criei três imagens: uma pequena (300x300), uma média (700x700) e uma grande (1000x1000). Utilizei a tag 'source:media:type' dentro da tag 'picture'. Essa tag é usada para fornecer várias fontes de imagens para um elemento 'img', permitindo que o navegador escolha a melhor imagem a ser exibida com base nas características do dispositivo do usuário.

Dentro da tag 'picture', adicionamos nossa imagem com a tag 'img', que será usada como base e que é a imagem de 1000x1000. Em seguida, criamos uma estrutura onde a ordem é crucial. Acima da tag 'img', adicionamos a tag 'source:media:type', onde incluímos a imagem média de 700x700. Sobre essa tag, adicionamos outra tag 'source:media:type' para a imagem pequena de 300x300.

Atenção aos elementos dos campos de atributos: no atributo 'media="(max-width: 1050px)"', ele serve para que a fonte seja aplicada apenas se a largura da tela for menor ou igual a 1050 pixels. No 'srcset="img/foto-m.png"': Este é o caminho para a imagem que será carregada se a condição de mídia especificada for atendida. Por fim, 'type="image/png"': Este atributo opcional especifica o tipo MIME da imagem.

Em relação ao áudio podemos usar a tag 'audio' e dentro dela usar o atributo 'controls' para controle de reprodução. Em seguida, usar a tag 'source' que é usada para especificar a fonte do arquivo de áudio. O atributo 'src' deve conter o caminho para o seu arquivo de áudio. O atributo 'type' especifica o tipo de arquivo de áudio (por exemplo, "audio/mp3" para arquivos MP3).

## EX012:
Ao abordar vídeos, enfrentamos pontos importantes, e assim como nas imagens, os direitos autorais devem ser tratados com seriedade. Nesse sentido, optamos por uma hospedagem local, ou seja, utilizamos a tag 'video' e incorporamos um vídeo qualquer (ATENÇÃO: alguns navegadores aceitam mp4, mpv ou outros formatos; no entanto, é importante considerar que a hospedagem local pode ser dispendiosa. Não é uma recomendação).

Outra abordagem envolve a utilização de vídeos do YouTube. Ao clicarmos em "compartilhar" e selecionarmos "incorporar", podemos copiar o código para o nosso arquivo index e utilizá-lo em nossa página web.

Uma terceira opção é utilizar o [vimeo](https://vimeo.com/pt-br/), que funciona de maneira semelhante ao YouTube.

## Desafio002:
A proposta desse desafio é aplicar o conhecimento adquirido sobre links e vídeos. O primeiro passo consisti em criar um arquivo index no qual eu inseri as thumbs dos vídeos desejados como links. Ao serem clicadas, essas thumbs redirecionam para uma página (sem abrir outra aba), onde estaria incorporado o vídeo do YouTube, um link para abrir uma nova aba com a playlist completa no YouTube e uma imagem de uma seta. Ao ser clicada, essa seta redirecionaria para a página principal.

Usei 4 vídeos do "canal em vídeo" para cada vídeo precisei criar um arquivo expecifico para cada um. Afinal das contas, a estrutura é a mesma, o que muda é os links e as imagens.

## EX013:
Inicializando em CSS, como primeiro passo aprendemos o "Estilo Inline" (os estilos são feito na mesma linha) onde aplicamos as cores e estilos localmente em cada tag. Atenção: não é o melhor jeito, desse jeito polui seu código.

## EX014:
Continuamos com o CSS e exploramos outra maneira de utilizá-lo. Neste exercício, empregamos "Estilos Locais", onde no cabeçalho do nosso código utilizamos a tag 'style'. Em seguida, criamos marcações, como no exemplo de 'h1', e fechamos a chave. Tudo o que definirmos como estilo será aplicado a todos os elementos 'h1', ou seja, é uma abordagem mais prática do que anterior.

## EX015:
O terceiro modo é, "Estilos Externo" onde criamos um arquivo 'style.css' (que é o lugar onde criamos as marcações de estilo) e ai conectamos com nosso arquivo index.html com link css. Conectando os arquivos e assim podendo mudar com uita mais organização e menos trabalho.

## EX016:
Aprofundando-nos nos estilos, podemos iniciar a discussão sobre o modelo RGB (Red, Green, Blue), que representa as cores em pixels. Ao modificar as tonalidades desses componentes, podemos criar uma vasta gama de cores. Existem várias formas de representação, como intervalos de 0 a 255, códigos hexadecimais e nomes de cores. Isso é ilustrado no exemplo 016.

