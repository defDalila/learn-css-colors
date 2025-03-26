# Lear CSS Colors By Building a Set of Colored Markers <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" style="width: 40px; fig-position:right; vertical-align:bottom; "/>


> Treinamento guiado de WEB Design da plataforma [FreeCodeCamp](https://www.freecodecamp.org/learn).
>

##  Objetivo :dart:

Aprender diferentes maneiras de definir valores de cores e como parear cores entre si utilizando o modelo RGB.


## :memo: Notas de Aula

- [x] Existem dois modelos principais de cores: o modelo aditivo RGB (vermelho, verde, azul), usado em dispositivos eletrônicos, e o modelo subtrativo CMYK (ciano, magenta, amarelo, preto), usado em impressão.

- [x] `rgb(red, green, blue);` Cada valor vermelho, verde e azul é um número de 0 a 255. 0 significa que há 0% dessa cor e 255 significa que há 100% dessa cor.

- [x] a palavra-chave de cor verde é, na verdade, um tom mais escuro, e está mais ou menos na metade do caminho entre o preto e o valor máximo para verde.

- [x] No modelo de cores RGB, cores primárias são cores que, quando combinadas, criam o branco puro. Mas para que isso aconteça, cada cor precisa estar em sua intensidade mais alta.
- [x] As cores secundárias são criadas pela combinação das cores primárias.
- [x] As cores terciárias são criadas pela combinação de uma cor primária com uma cor secundária próxima.
- [X] O modelo de cor HSL, ou matiz, saturação e luminosidade, é outra maneira de representar cores.
- [X] A função CSS hsl aceita 3 valores: um número de 0 a 360 para matiz, uma porcentagem de 0 a 100 para saturação e uma porcentagem de 0 a 100 para luminosidade.
- [X] Supondo uma roda de cores, o matiz vermelho está em 0 graus, o verde está em 120 graus e o azul está em 240 graus.
- [x] Saturação é a intensidade de uma cor de 0%, ou cinza, a 100% para cor pura. É necessário adicionar o sinal de porcentagem % aos valores de saturação e luminosidade.
- [x] Luminosidade é o quão "brilhante" uma cor que vai de de 0%, ou preto completo, a 100%, branco completo onde 50% é uma luminosidade  neutra.
- [x] Gradiente é quando uma cor faz a transição para outra. A função CSS linear-gradient permite que você controle a direção da transição ao longo de uma linha e quais cores são usadas.
- [x] A função `linear-gradient`  cria um elemento de imagem e geralmente é vinculada com a propriedade `background`, que pode aceitar uma imagem como valor.
- [x] Opacidade descreve o quão opaco, ou seja, não transparente, algo é. 
- [x] Com a propriedade opacity do CSS, é possível controlar o quão opaco ou transparente um elemento é. Definindo o valor 0, ou 0%, o elemento será completamente transparente, e definindo 1.0, ou 100%, o elemento será completamente opaco como é por padrão.
- [x] Outra maneira de definir a opacidade para um elemento é com o canal alfa. Semelhante à propriedade de opacidade, o canal alfa controla quão transparente ou opaca uma cor é.
- [x] rgba(255, 255, 255, 0.5);


<br>

### :star: Cores Primárias :star:

<pre>
- Red:   <font color='red'>rgb(255, 0, 0)</font>  |  <font color='red'>hsl(0, 100%, 50%)</font>

- Green: <font color='#007f00'><strong>rgb(0, 255, 0)</strong></font>  |  <font color='#007f00'><strong>hsl(120, 100%, 50%)</strong></font>
  
- Blue:  <font color='blue'><strong>rgb(0, 0, 255)</strong></font>  |  <font color='blue'><strong>hsl(240, 100%, 50%)</strong></font>
</pre>

<br>

### :star: Cores Secundárias:star:

<pre>
- White:   <font color='#ffffff'><strong>rgb(255, 255, 255)</strong></font>

- Yellow:  <font color='#ffff00'><strong>rgb(255, 255, 0)</strong></font>
  
- Cyan:    <font color='#00ffff'><strong>rgb(0, 255, 255)</strong></font>

- Magenta: <font color='#ff00ff'><strong>rgb(255, 0, 255)</strong></font>
</pre>

<br>

### :star: Cores Terciárias:star:

<pre>
- Orange:            <font color='#ff7f00'><strong>rgb(255, 127, 0)</strong></font>

- Spring Green:      <font color='#00ff7f'><strong>rgb(0, 255, 127)</strong></font>
  
- Violet:            <font color='#7f00ff'><strong>rgb(127, 0, 255)</strong></font>

- Chartreuse green:  <font color='#7fff00'><strong>rgb(127, 255, 0)</strong></font>
  
- Azure:             <font color='#007fff'><strong>rgb(0, 127, 255)</strong></font>

- Bright Pink:       <font color='#ff007f'><strong>rgb(255, 0, 127)</strong></font>
</pre>