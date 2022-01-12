# 💻Estudos Digital Innovation One

🖊️Anotações das aulas do Bootcamp da Digital Innovation One em parceria com o banco Inter. 

---

## 👩‍💻Introdução a criação de site com HTML5 e CSS3

---

### Semântica

✔️`<section>` seção genérica de conteúdo <br>
✔️`<header>` cabeçalho de uma página ou de parte da página <br>
✔️`<article>` representa um conteúdo relevante em uma página <br>
✔️`<footer>`  rodapé da página ou de parte da página <br>
✔️`<h1>` ... `<h6>` representam a importância de um título dentro de uma página, só pode haver um h1 por página <br>

---

### Textos e links 

✔️`<h1>` Título da página `</h1>` <br>
✔️`<h2>` Título da seção `</h2>` <br>
✔️`<h3>` Título de artigo `</h3>` <br>
✔️`<p>` Conteúdo do artigo `</p>` <br>

✔️O elemento `<a>` tem dois atributos principais: <br>
1° - hiperlink (href) - hiperlink para onde âncora está apontando <br>
✔️`<a href="linkedin.com/in/vilaboim"> Linkedin </a>` <br>
✔️`<a href="mailto:evcm@email.com"> Email </a>` <br>

###### Obs: mailto - email/tel - telefone <br>

2° - target - indica como o link pode ser aberto <br>
✔️`<a target="_blank"> Link </a>` <br>

###### Obs: blank indica que o link será aberto em uma nova aba <br>

---

### Como inserir imagens em seu site

✔️O elemento `<img>` possui apenas dois atributos próprios <br>
1° - src (obrigatório) - guarda o caminho da imagem <br>
2° - alt (recomendado) - mostra a descrição da foto quando ela não é carregada <br>

---

### Como organizar listas com html

✔️`<ul>` - lista não ordenada <br>
✔️`<ol>` - lista ordenada <br>
✔️`<li>` - elemento de lista <br>

---

### Introdução e conceitos básicos do CSS

---

#### Introdução a CSS3
Requisitos básicos <br>
✔️Editor de texto <br>
✔️Um navegador de internet <br>
✔️Conhecimento em html <br>

Estrutura do css <br>
✔️Seletores: elementos html <br>
✔️Declaração: propriedade + valor <br>
Exemplo: `a, h1, h2{color: green}` <br>

Id e divs <br>
✔️`Id` (#) `div` (.) <br>
✔️O Id só pode ser usado uma vez por página <br>


#### Conceitos básicos do CSS

Box model <br>
✔️Margin - espaçamento entre elementos <br>
✔️Border - circundam o padding e o conteúdo <br>
✔️Padding - espaçamento entre a borda e o conteúdo <br>
✔️Content - o que o bloco representa (texto, imagem ou vídeo) <br>

---

### Estilizando elementos, textos e listas

---

#### Estilizando elementos

Como atribuir valores diferentes para cada lado <br>
✔️Padding/margin: <br>
`.post {padding: 10px 5px;}` <br>
10px - parte superior e inferior <br>
5px - lado esquerdo e direito <br>
`.post {padding: 15px 10px 5px 0;}` <br>
15px - parte superior <br>
10px - lado direito <br>
5px - parte inferior <br>
0 - lado esquerdo <br>
`.post {padding-top: 15px padding-left:10px padding-bottom:5px padding-right:0;}` <br>

Como mudar a cor de fundo <br>
✔️Background <br>
`.post {background-color: black;}` <br>
`.post {background-color: #000;}` <br>
`.post {background: #000;}` <br>

✔️Border <br>
Largunra: px, cm, ml... <br>
Cor: black. #000... <br>
Esilo: solida, pontilhada, tracejada... <br>
Radius: px e porcentagem <br>
`.post{border: 3px solid blue; border-top: 2px dotted green; border-right: 4px dashed pink;}` <br>

#### Estilizando textos

✔️Font-family <br>
`#title {font-family: verdana;}` - adcionando apenas um tipo de fonte ao texto <br>
`#title {font-family: verdana, arial;}` - adcionando dois tipos de fonte pois assim caso a primeira não funcione, a segunda será usada <br>

✔️Font-size <br>
`#title {font-size: 10px;}` - adcionando tamanho de 10px para a font <br>

✔️Font-style <br>
`#title {font-style: italic;}` - mudando a fonte para italica <br>

✔️Font-weight <br>
`#title {font-weight: bold;}` - alterando o peso da fonte para negrito <br>

✔️Text-tranform <br>
`#title {text-tranformt: uppercase;}` - coloca todo o texto em caixa alta <br>
`#title {text-tranformt: lowercase;}` - coloca todo o texto em caixa baixa <br> 
`#title {text-tranformt: capitalize;}` - coloca todo as primeiras letras de cada palavra maiúscula <br> 

✔️Text-tdecoration <br>
`#title {text-decoration: underline;}` - coloca linha abaixo da palavra <br> 
`#title {text-decoration: overline;}` - coloca linha acima da palavra <br> 
`#title {text-decoration: line-through;}` - coloca linha ao centro da palavra <br> 

#### Estilizando listas

✔️List-style-type <br>
`ul{list-style-type: square;}` - altera o marcador da lista para um quadrado <br> 
`ol{list-style-type: uper-roman;}`- altera o marcador da lista para um algorismo romano maiusculo <br>
`ul{list-style-type: "#\1F44D";}`- altera o marcador da lista para um simbolo (nesse caso, um emogi) <br> 

✔️List-style-image <br>
`ul{list-style-image: url(rocket.com);}` - altera o marcador da lista para uma imagem <br> 

---

### Propriedades de dimensões e alinhamento

✔️Widht - ajusta a largura <br>
✔️Height - ajusta a altura <br>
✔️Max-widht - largura máxima do elemento <br>
✔️Max-height - largura mínima <br>
✔️Margin - espaçamento em elemento, o valor auto alinha o elemente automaticamente <br>
✔️Text-align - alinha o texto <br>
 









