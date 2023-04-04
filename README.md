# Conceitos CSS

<ul>
	<a href="">Fundamentos do CSS</a>
	<li></li>
	<a href="">Estilização Básica com CSS</a>
	<li></li>
	<a href="">Cores</a>
	<li></li>
	<a href="">Imagens</a>
	<li></li>
	<a href="">Bordas</a>

</ul>

## Fundamentos do CSS
CSS (Cascading Style Sheets) é uma linguagem de estilo utilizada para estilizar páginas web, permitindo a criação de layouts atraentes e agradáveis ​​ao usuário.

O CSS é composto por regras que definem como um elemento HTML deve ser exibido na página. Essas regras incluem propriedades, que são usadas para especificar as características do elemento, como cor, tamanho, fonte, posicionamento e outras. As propriedades podem ser definidas em um estilo inline (dentro do elemento HTML), em um arquivo CSS externo ou em um estilo incorporado (no cabeçalho do documento HTML).

Além disso, o CSS permite que os desenvolvedores criem regras que afetam várias partes do documento HTML. Isso é feito através do uso de seletores, que permitem direcionar elementos específicos ou grupos de elementos. Os seletores são combinados com as propriedades para criar estilos personalizados para diferentes elementos.

O CSS também tem a capacidade de criar efeitos de transição e animação, permitindo que os desenvolvedores criem páginas dinâmicas e interativas. Além disso, o CSS oferece recursos para tornar as páginas web responsivas, permitindo que sejam exibidas corretamente em diferentes dispositivos e tamanhos de tela.

No geral, o CSS é uma parte fundamental do desenvolvimento web moderno, permitindo que os desenvolvedores criem páginas atraentes e funcionais que proporcionam uma experiência de usuário positiva.

### O que pode ser criado?
Com o CSS, é possível criar uma ampla variedade de estilos e efeitos visuais para as páginas web. Algumas das coisas que podem ser criadas com CSS incluem:

<b>• Layouts responsivos:</b> os layouts responsivos são aqueles que se ajustam automaticamente ao tamanho da tela do dispositivo em que são exibidos. Isso permite que as páginas sejam exibidas corretamente em diferentes dispositivos, como desktops, laptops, tablets e smartphones.

<b>• Animações e transições:</b> o CSS permite criar animações e transições para elementos específicos da página, como botões, imagens e textos. Isso pode ajudar a tornar a página mais interativa e atraente para os usuários.

<b>Tipografia personalizada:</b> com o CSS, é possível escolher fontes personalizadas para os elementos de texto da página, incluindo tamanhos, estilos e cores.

<b>• Cores e fundos:</b> o CSS permite definir cores personalizadas para os elementos da página, incluindo o fundo. Isso pode ser usado para criar um esquema de cores atraente e consistente em toda a página.

<b>• Efeitos de imagem:</b> o CSS oferece recursos para criar efeitos de imagem, como filtros e opacidade. Isso pode ser usado para criar imagens personalizadas e atraentes para a página.

No geral, o CSS é uma ferramenta poderosa para criar estilos e efeitos visuais para as páginas web, permitindo que os desenvolvedores criem páginas atraentes e funcionais que proporcionam uma experiência de usuário positiva.

### Formas de declaração do CSS
Existem três maneiras de declarar o CSS (Cascading Style Sheets):

<b>• Estilos inline:</b> os estilos inline são aplicados diretamente aos elementos HTML usando o atributo <b>"style"</b>. Os estilos inline são usados para aplicar estilos específicos a um único elemento HTML. 

	<p style="color: red; font-size: 16px;">Este é um parágrafo com estilo inline</p>

<b>• Estilos incorporados:</b> os estilos incorporados são definidos no cabeçalho do documento HTML, usando a tag <b>"style"</b>. Os estilos incorporados são usados para aplicar estilos a vários elementos HTML em uma única página.

	<head>
	  <style>
	    p {
	      color: red;
	      font-size: 16px;
	    }
	  </style>
	</head>

<b>• Folhas de estilo externas:</b> as folhas de estilo externas são arquivos <b>CSS separados</b> que contêm todos os estilos para uma página ou um site inteiro. As folhas de estilo externas são <b>vinculadas à página HTML</b> usando a tag <b>"link"</b>.

	<head>
	  <link rel="stylesheet" href="style.css">
	</head>

As folhas de estilo externas são a forma mais <b>recomendada</b> de definir estilos CSS, pois permitem que os estilos sejam <b>reutilizados em várias páginas</b> e mantidos em um <b>único arquivo CSS</b>. Além disso, as folhas de estilo externas também permitem que o cache do navegador armazene os estilos, o que pode melhorar o desempenho da página.

## Seletores
Os seletores são usados no CSS (Cascading Style Sheets) para <b>direcionar e selecionar</b> elementos HTML específicos que desejamos estilizar. Os seletores são usados em conjunto com as propriedades CSS para aplicar estilos a elementos específicos.


### Seletor de elemento
<b>• Seletor de elemento:</b> este seletor é usado para selecionar elementos HTML específicos. Por exemplo, o seletor <b>"p"</b> é usado para selecionar todos os elementos de parágrafo na página:

	p {
	font-size: 16px;
	color: red;
	}

### Seletor de ID
<b>• Seletor de ID:</b> este seletor é usado para selecionar um elemento HTML com um <b>ID específico</b>. O ID é definido no HTML usando o atributo <b>"id"</b>. Por exemplo, o seletor <b>"#header"</b> é usado para selecionar um elemento com o ID "header":

	#header {
	background-color: blue;
	height: 100px;
	}

### Seletor de Classe
<b>• Seletor de classe:</b> este seletor é usado para selecionar elementos HTML com uma <b>classe específica</b>. A classe é definida no HTML usando o <b>atributo "class"</b>. Por exemplo, o seletor <code>".destaque"</code> é usado para selecionar todos os elementos com a <b>classe "destaque"</b>:

	.destaque {
	border: 2px solid yellow;
	padding: 10px;
	}

### Seletor de Descendente
<b>• Seletor de descendente:</b> este seletor é usado para selecionar um elemento HTML <b>dentro de outro elemento</b> HTML. Por exemplo, o seletor <b>"ul li"</b> é usado para selecionar todos os elementos de lista dentro de uma lista não ordenada:

	ul li {
	font-size: 14px;
	color: green;
	}

### Seletor de filho
<b>• Seletor de filho:</b> este seletor é usado para selecionar um elemento HTML que é um filho direto de outro elemento HTML. Por exemplo, o seletor "div > p" é usado para selecionar todos os elementos de parágrafo que são filhos diretos de uma div:

div > p {
font-size: 18px;
color: blue;
}

Esses são só alguns seletores que mencionei, existem outros.

## Combinadores
Os combinadores são usados para selecionar elementos HTML <b>com base em sua relação com outros elementos</b> HTML. Existem quatro tipos de combinadores:

### Combinador de descendente (espaço)
<b>• Combinador de descendente (espaço):</b> o combinador de descendente é usado para selecionar elementos HTML que são <b>descendentes de outro elemento HTML</b>. Por exemplo, o seletor <b>"div p"</b> é usado para selecionar todos os elementos de parágrafo que são descendentes de uma div.

	<div>
	  <p>Este é um parágrafo dentro da div</p>
	</div>
	Combinador de filho direto (>): o combinador de filho direto é usado para selecionar elementos HTML que são filhos diretos de outro elemento HTML. Por exemplo, o seletor "div > p" é usado para selecionar todos os elementos de parágrafo que são filhos diretos de uma div.

	<div>
	  <p>Este é um parágrafo dentro da div</p>
	  <span>
	    <p>Este é um parágrafo dentro de uma span</p>
	  </span>
	</div>

### Combinador de irmão adjacente (+)
<b>• Combinador de irmão adjacente (+):</b> o combinador de irmão adjacente é usado para <b>selecionar o primeiro</b> elemento HTML que é irmão adjacente de outro elemento HTML. Por exemplo, o seletor <b>"h1 + p"</b> é usado para selecionar o primeiro elemento de parágrafo que é irmão adjacente de um elemento h1.

	<h1>Título</h1>
	<p>Este é o primeiro parágrafo após o título</p>
	<p>Este é o segundo parágrafo após o título</p>

### Combinador de irmão geral (~)
<b>• Combinador de irmão geral (~):</b> o combinador de irmão geral é usado para selecionar todos os elementos HTML que são irmãos de outro elemento HTML. Por exemplo, o seletor "h1 ~ p" é usado para selecionar todos os elementos de parágrafo que são irmãos de um elemento h1.

	<h1>Título</h1>
	<p>Este é o primeiro parágrafo após o título</p>
	<span>
	  <p>Este é um parágrafo dentro de uma span</p>
	</span>
	<p>Este é o segundo parágrafo após o título</p>

Os combinadores são uma maneira poderosa de selecionar e estilizar elementos HTML com base em sua relação com outros elementos HTML. Combinados com os seletores, eles permitem uma grande flexibilidade na criação de estilos complexos e personalizados para páginas da web.

## Propriedades de Dimensionamento e Espaçamento
As propriedades de dimensionamento e espaçamento são usadas para definir o tamanho e o espaço dos elementos HTML. Aqui estão algumas das principais propriedades de dimensionamento e espaçamento:

### Width
<b>• width:</b> define a largura do elemento HTML. Pode ser definida em pixels, porcentagem ou outras unidades de medida.

	div {
	width: 300px;
	}

### Height
<b>•height:</b> define a altura do elemento HTML. Pode ser definida em pixels, porcentagem ou outras unidades de medida.

	div {
	height: 200px;
	}

### Padding
<b>• padding:</b> define o espaço interno do elemento HTML. O espaço interno é a área entre o conteúdo do elemento e sua borda.

	div {
	padding: 10px;
	}

### Margin
<b>• margin:</b> define o espaço externo do elemento HTML. O espaço externo é a área entre o elemento e outros elementos ao seu redor.

	div {
	margin: 20px;
	}

### Border
<b>• border:</b> define a borda do elemento HTML. A borda é uma linha que envolve o elemento.

	div {
	border: 1px solid black;
	}

### Box-sizing
<b>• box-sizing:</b> define como a largura e a altura do elemento HTML são calculadas. O valor padrão é content-box, que inclui apenas o conteúdo no cálculo da largura e da altura. O valor border-box inclui a borda e o padding no cálculo da largura e da altura.

	div {
	box-sizing: border-box;
	}

Essas são algumas das principais propriedades de dimensionamento e espaçamento no CSS. Elas permitem que os desenvolvedores controlem com precisão o tamanho e o espaço dos elementos HTML em suas páginas da web.

## Estilização Básica com CSS
A estilização básica envolve a definição de estilos para elementos HTML, como <b>cor de fundo, cor do texto, tamanho da fonte e outros atributos visuais</b>. Aqui estão algumas das propriedades mais comuns usadas na estilização básica com CSS:

### Background-color
<b>• background-color:</b> define a cor de fundo do elemento HTML.

	div {
	background-color: #f0f0f0;
	}

### Color
<b>• color:</b> define a cor do texto do elemento HTML.

	div {
	color: #333;
	}

### Font-size
<b>• font-size:</b> define o tamanho da fonte do texto do elemento HTML.

	div {
	font-size: 16px;
	}

### Font-family
<b>• font-family:</b> define a família de fontes usada pelo texto do elemento HTML.

	div {
	font-family: Arial, sans-serif;
	}

### Text-align
<b>• text-align:</b> define o alinhamento do texto do elemento HTML.

	div {
	text-align: center;
	}

### Border-radius
<b>• border-radius:</b> define o raio dos cantos da borda do elemento HTML.

	div {
	border-radius: 5px;
	}

Essas são apenas algumas das propriedades que podem ser usadas na estilização básica com CSS. As possibilidades de estilização são praticamente infinitas e dependem da criatividade e habilidade do desenvolvedor. Com o uso de seletores e outras técnicas avançadas do CSS, é possível criar estilos complexos e personalizados para páginas da web.

## Cores
As cores são uma parte importante do design visual em páginas da web e podem ser definidas. Aqui estão algumas formas de definir cores em CSS:

### Nome da cor
<b>• Nome da cor:</b> algumas cores têm nomes predefinidos no CSS, como red, blue, green e black. Esses nomes podem ser usados diretamente para definir a cor de um elemento HTML.

	div {
	background-color: red;
	}

### Código hexadecimal
<b>• Código hexadecimal:</b> as cores também podem ser definidas usando códigos hexadecimais de seis dígitos, que representam a quantidade de vermelho, verde e azul (RGB) em uma cor.

	div {
	background-color: #ff0000;
	}

### RGB
<b>• RGB:</b> as cores também podem ser definidas usando a função rgb(), que especifica o valor de vermelho, verde e azul em uma cor.

	div {
	background-color: rgb(255, 0, 0);
	}

<b>• RGBA:</b> a função rgba() é semelhante à função rgb(), mas também permite definir a transparência da cor.

	div {
	background-color: rgba(255, 0, 0, 0.5);
	}

### HSL e HSLA
HSL (Hue, Saturation, Lightness) e HSLA (Hue, Saturation, Lightness, Alpha) são formas alternativas de definir cores em CSS (HUE, HSL e HSLA são conceitos de cores em UX/UI).

A definição da cor no modelo HSL consiste em três valores: matiz (hue), saturação (saturation) e luminosidade (lightness). O matiz é um valor entre 0 e 360 graus, que representa a cor (por exemplo, vermelho, verde, azul). A saturação é um valor entre 0% e 100%, que representa a pureza da cor (100% significa que a cor é pura, enquanto 0% significa que a cor é cinza). A luminosidade é um valor entre 0% (preto) e 100% (branco), que representa o brilho da cor.

	div {
	background-color: hsl(240, 100%, 50%);
	}

A definição da cor no modelo HSLA é semelhante à HSL, mas também permite definir a transparência da cor, usando um valor de alfa entre 0 e 1.

	div {
	background-color: hsla(240, 100%, 50%, 0.5);
	}

O uso do modelo HSL e HSLA pode oferecer uma maneira mais intuitiva de definir cores, pois permite controlar facilmente o matiz, a saturação e a luminosidade de uma cor. É importante lembrar que nem todos os navegadores oferecem suporte total a esses modelos, então é sempre bom verificar a compatibilidade antes de usá-los em um projeto.

## Imagens
As imagens são um elemento fundamental em muitas páginas da web e podem ser estilizadas usando CSS (No framework Bootstrap tem a classe "img-fluid" que dimensiona para visualizar em dispositivos diferentes). Algumas das propriedades CSS que podem ser usadas para estilizar imagens incluem:

### Width e Height
<b>• width e height:</b> estas propriedades são usadas para definir a <b>largura e a altura</b> de uma imagem.

img {
width: 300px;
height: 200px;
}

### Max-width e Max-height
<b>• max-width e max-height:</b> essas propriedades definem a <b>largura e a altura máximas</b> que uma imagem pode ter. Isso é útil para garantir que as imagens não fiquem muito grandes em telas maiores.

	img {
	max-width: 100%;
	max-height: 100%;
	}


### Object-fit
<b>• object-fit:</b> esta propriedade define como a imagem <b>deve se ajustar ao contêiner</b>. Os valores dele incluem <b>cover</b> (a imagem é redimensionada para preencher o contêiner enquanto mantém a proporção), <b>contain</b> (a imagem é redimensionada para caber no contêiner enquanto mantém a proporção) e <b>fill</b> (a imagem é redimensionada para preencher o contêiner, ignorando a proporção).

	img {
	width: 300px;
	height: 200px;
	object-fit: cover;
	}

### border-radius
<b>• border-radius:</b> esta propriedade define o raio dos cantos da imagem, tornando possível criar imagens com <b>bordas arredondadas</b> (sendo possível criar imagens círculares, que no framework Bootstrap é a class img-circle).

	img {
	border-radius: 50%;
	}

Essas são apenas algumas das propriedades CSS que podem ser usadas para estilizar imagens em páginas da web. Ao combiná-las com outras propriedades CSS, como position e transition, pode criar efeitos visuais interessantes e atraentes.

## Fundo dos Elementos 
O fundo dos elementos pode ser estilizado de várias maneiras usando CSS. Algumas das propriedades mais comuns usadas para estilizar o fundo dos elementos incluem:

### background-color
<b>• background-color:</b> essa propriedade define a cor de fundo de um elemento.

	div {
	background-color: #F5F5F5;
	}


### Background-image
<b>• background-image:</b> esta propriedade define uma imagem de fundo para um elemento.

	div {
	background-image: url("imagem.jpg");
	}

### Background-repeat
<b>• background-repeat:</b> essa propriedade define como a imagem de fundo deve se repetir, se for menor do que o elemento em que está contido. Os valores possíveis incluem repeat (repetir a imagem na horizontal e na vertical), repeat-x (repetir a imagem apenas na horizontal), repeat-y (repetir a imagem apenas na vertical) e no-repeat (não repetir a imagem, boa para fundos com imagens que precisa de destaque).

	div {
	background-image: url("imagem.jpg");
	background-repeat: no-repeat;
	}

### Background-size
<b>• background-size:</b> esta propriedade define o tamanho da imagem de fundo. Os valores possíveis incluem auto (tamanho original da imagem), cover (redimensionar a imagem para preencher o elemento) e contain (redimensionar a imagem para caber no elemento).

div {
background-image: url("imagem.jpg");
background-size: cover;
}

background-position: esta propriedade define a posição inicial da imagem de fundo. Os valores possíveis incluem top, bottom, left, right e center.

div {
background-image: url("imagem.jpg");
background-position: center;
}

Essas são apenas algumas das propriedades CSS que podem ser usadas para estilizar o fundo dos elementos em páginas da web (uma dica que dou é criar uma div em que a imagem fica na class dela e, quando precisar usar na página, usa a div com a class, assim pode mexer no width, height entre outros sem afetar a imagem)

## Bordas
