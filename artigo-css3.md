####Universidade do Oeste de Santa Catarina – Unoesc
####Pós-Graduação em Desenvolvimento Web, Cloud e Dispositivos Móveis - WebMob
####Disciplina: HTML5+CSS3
####Professor: Jean Carlo Nascimento
####Acadêmico: Maurício Alberto Grando
###Artigo de Revisão de CSS3

#####Funcionalidade: Cores HSLA
#####O que é?
A propriedade HSLA destina-se a definir cores e transparência com uso de valores para matiz (Hue), saturação (Saturation) e luminosidade (Lightness).
#####Onde usar:
Em qualquer elemento que possui o atributo background.
#####Como usar:
``` css
seletor { propriedade: hsla(H, S, L, A); } 
```
#####Exemplo de uso:
A sintaxe geral para aplicar cores e transparência é mostrada a seguir.
``` css
seletor { 
     background: hsla(0, 0%, 0%, 1); 
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/hsla.php] (http://www.maujor.com/tutorial/interativo-css3/inc/hsla.php)
<br/><br/>
#####Funcionalidade: Text Shadow
#####O que é?
A propriedade text-shadow destina-se a definir sombras em textos.
#####Onde usar:
Em qualquer elemento que possui o atributo text.
#####Como usar:
```css
seletor { propriedade: offsetX offsetY raioBlur cor [,offsetX offsetY raioBlur cor];}
```
Os valores de raioBlur e cor são opcionais.
#####Exemplo de uso:
A sintaxe geral para aplicar sombreamento em textos é mostrada a seguir.
```css
seletor { 
      text-shadow: 0 0 0 0 none;
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/textshadow.php] (http://www.maujor.com/tutorial/interativo-css3/inc/textshadow.php)
<br/><br/>
#####Funcionalidade: Cores RGBA
#####O que é?
A propriedade RGBA destina-se a definir cores e transparência com uso de valores RGB (sistema de cores formado por Red, Green e Blue).
#####Onde usar:
Em qualquer elemento que possui propriedades de cor. Exemplos: color, background, border-color, etc).
#####Como usar:
```css
seletor { propriedade: rgba(R, G, B, A); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar cores é mostrada a seguir.
```css
seletor { 
      background: rgba(0, 0, 0, 1);
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/rgba.php] (http://www.maujor.com/tutorial/interativo-css3/inc/rgba.php)
<br/><br/>
#####Funcionalidade: Transform 2D – Skew
#####O que é?
Essa transformação causa a inclinação dos lados de um box em relação aos eixos x e/ou y.
#####Onde usar:
Em qualquer elemento que possui o atributo transform.
#####Como usar:
Os valores da inclinação devem ser especificados em medida css para ângulos, ou seja, deg, grad, rad e turn. São admitidos valores negativos e positivos causando inclinação em um ou outro sentido.
```css
seletor { transform: skew(adeg, ßdeg); } 
seletor { transform: skewX(adeg); } 
seletor { transform: skewY(ßdeg); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar skew é mostrada a seguir.
```css
seletor {
  -webkit-transform: skew(0, 0);
  -moz-transform: skew(0, 0);
  -o-transform: skew(0, 0);
  -ms-transform: skew(0, 0);
  transform: skew(0, 0);
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/skew2d.php] (http://www.maujor.com/tutorial/interativo-css3/inc/skew2d.php)
<br/><br/>
#####Funcionalidade: Transform 2D – Translate
#####O que é?
Essa transformação causa a translação de um elemento ao longo dos eixos x e/ou y.
#####Onde usar:
Em qualquer elemento que possui o atributo transform.
#####Como usar:
Valores positivos de x expressam deslocamento para a direita e valores positivos de y deslocamento para baixo. Valores negativos expressam deslocamento em sentido contrário ao descrito.
```css
seletor { transform: translate(x, y); } 
seletor { transform: translateX(x); } 
seletor { transform: translateY(y); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar translate é mostrada a seguir.
```css
seletor {
  -webkit-transform: translate(0px, 0px);
  -moz-transform: translate(0px, 0px);
  -o-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/translate2d.php] (http://www.maujor.com/tutorial/interativo-css3/inc/translate2d.php)
<br/><br/>
#####Funcionalidade: Transform 2D – Rotate
#####O que é?
Essa transformação causa a rotação de um elemento. A rotação deve ser expressa em medida css para ângulos, ou seja, deg, grad, rad e turn.
#####Onde usar:
Em qualquer elemento que possui o atributo transform.
#####Como usar:
Valores positivos causam rotação no sentido horário e valores negativos no sentido anti-horário.
```css
seletor {transform: rotate(adeg); } 
seletor {transform: rotateX(adeg); } 
seletor {transform: rotateY(adeg); } 
seletor {transform: rotateZ(adeg); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar rotação é mostrada a seguir.
```css
seletor {
  -webkit-transform: rotate(0deg);
  -moz-transform: rotate(0deg);
  -o-transform: rotate(0deg);
  -ms-transform: rotate(0deg);
  transform: rotate(0deg);
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/rotate2d.php] (http://www.maujor.com/tutorial/interativo-css3/inc/rotate2d.php)
<br/><br/>
#####Funcionalidade: Transform 2D – Scale
#####O que é?
Essa transformação causa o aumento/redução das dimensões de um elemento ao longo dos eixos x e/ou y.
#####Onde usar:
Em qualquer elemento que possui o atributo transform.
#####Como usar:
Valores maiores que 1 expressam aumento e valores entre 0 e 1 diminuição das dimensões. N é um número que expressa à quantidade de vezes a aumentar ou diminuir, ou seja, o fator de multiplicação das dimensões.
```css
seletor { transform: scale(x, y); } 
seletor { transform: scaleX(x); } 
seletor { transform: scaleY(y); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar aumento/redução das dimensões é mostrada a seguir.
```css
seletor {
  -webkit-transform: scale(1, 1);
  -moz-transform: scale(1, 1);
  -o-transform: scale(1, 1);
  -ms-transform: scale(1, 1);
  transform: scale(1, 1);
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/scale2d.php] (http://www.maujor.com/tutorial/interativo-css3/inc/scale2d.php)
<br/><br/>
#####Funcionalidade: Expressões Matemáticas
#####O que é?
A função calc() permite que se definam valores css com uso de expressões matemáticas, ou seja, o valor adotado para a propriedade é o resultado de uma expressão matemática.
#####Onde usar:
Em qualquer elemento que possui atributos numerados (podendo ser em pixels ou %).
#####Como usar:
Os operadores matemáticos válidos são: + (soma), - (subtração), * (multiplicação) e / (divisão). As unidades de medida css válidas na expressão matemática são as unidades css para: comprimento, ângulo, tempo, frequência e números inteiros e fracionários.
Na expressão matemática que define o valor css é permitido que sejam misturadas diferentes unidades de medida. A sintaxe geral para uso desta função é conforme mostrada a seguir:
```css
seletor { propriedade: calc(expressão matemática); }
```
#####Exemplo de uso:
A sintaxe geral para aplicar expressões matemáticas nos atributos é mostrada a seguir.
```css
seletor {
width: calc(100% - 100px); 
}
```
#####Referência:
[http://www.maujor.com/tutorial/css3-funcao-css-calc.php] (http://www.maujor.com/tutorial/css3-funcao-css-calc.php)
<br/><br/>
#####Funcionalidade: Box Shadow
#####O que é?
Essa transformação aplica sombras em box’s, ou qualquer tipo de elemento em uma página html.
#####Onde usar:
Em qualquer elemento.
#####Como usar:
É necessário informar os parâmetros indicando o deslocamento horizontal e vertical da sombra, esfumaçado e cor da sombra.
```css
seletor { propriedade: none|h-shadow v-shadow blur spread color |inset|initial|inherit; }
```
#####Exemplo de uso:
A sintaxe geral para aplicar sombreamento em caixas é mostrada a seguir.
```css
seletor {
    box-shadow: 5px 5px 0 #333;
   -webkit-box-shadow: 5px 5px 0 #333;
   -moz-box-shadow: 5px 5px 0 #333;
}
```
#####Referência:
[http://www.linhadecodigo.com.br/artigo/3633/entendendo-o-atributo-box-shadow-nas-css3.aspx] (http://www.linhadecodigo.com.br/artigo/3633/entendendo-o-atributo-box-shadow-nas-css3.aspx)
[http://www.w3schools.com/cssref/css3_pr_box-shadow.asp] (http://www.w3schools.com/cssref/css3_pr_box-shadow.asp)
<br/><br/>
#####Funcionalidade: Gradiente
#####O que é?
Gradientes permitem exibir transições suaves entre duas ou mais cores especificadas.
#####Onde usar:
Em qualquer elemento que contém o atributo background.
#####Como usar:
Existem dois tipos de gradientes: linear (são definidas pelo menos duas cores de parada) e radial (é definido pelo seu centro).
```css
seletor { propriedade: linear-gradient(direction, color-stop1, color-stop2, ...);}
seletor { propriedade: radial-gradient(shape size at position, start-color, ..., last-color);}
```
#####Exemplo de uso:
A sintaxe geral para aplicar gradiente (linear e radial) pode variar conforme o navegador utilizado. Abaixo são exibidas sintaxes para alguns navegadores.
```css
seletor {
  background: -webkit-linear-gradient(red, blue); /* For Safari 5.1 to 6.0 */
  background: -o-linear-gradient(red, blue); /* For Opera 11.1 to 12.0 */
  background: -moz-linear-gradient(red, blue); /* For Firefox 3.6 to 15 */
  background: linear-gradient(red, blue); /* Standard syntax */
}
seletor {
  background: -webkit-radial-gradient(red, green, blue); /* Safari 5.1 to 6.0 */
  background: -o-radial-gradient(red, green, blue); /* For Opera 11.6 to 12.0 */
  background: -moz-radial-gradient(red, green, blue); /* For Firefox 3.6 to 15 */
  background: radial-gradient(red, green, blue); /* Standard syntax */
}
```
#####Referência:
[http://www.w3schools.com/css/css3_gradients.asp] (http://www.w3schools.com/css/css3_gradients.asp)
<br/><br/>
