## Exercícios de Revisão - Usabilidade, Desenvolvimento Web, Mobile e Jogos
&nbsp;

__1. Observe o exemplo de um formulário HTML abaixo:__

![](formulario.png)

a)  Crie um formulário em HTML similar ao mostrado na imagem, contendo os mesmos campos.

b) Qual é a função dos atributos action e method da tag \<form\>?

c) Deixe a página similar à imagem abaixo utilizando CSS.

Considere que:

* A fonte utilizada é arial.
* As margens à esquerda e à direita têm 50px.
* As cores utilizas são preto (black) para o fundo e laranja (orange) para o botão e para o campo de texto.

![](formulario_css.png)

d) Explique a diferença entre o \<link\> e o \<style\> no contexto do CSS.


&nbsp;

__2. Analise o seguinte código JavaScript:__

```
function changeInnerHtml() {
    let valor = document.getElementById("myinput").value;

    document.getElementById("mydiv").innerHTML = valor;
}
```

a) Explique o que código faz.

b) O que o document.getElementById faz? Qual é a diferença entre ele e o document.getElementsByClassName e o document.getElementsByTagName?

&nbsp;

__3. Escreva o código CSS correspondente a cada uma das descrições:__

Exemplo: 

- Coloque uma margem à esquerda de 2px em todas os parágrafos descendentes de uma div:

    ```
    div p {
        margin-left: 2px;
    }
    ```

a) Mude a cor de fundo para preto de do elemento com id "telapreta".

b) Faça com que todos os elementos \<li\> descendentes de elementos da classe "menu" tenham fundo preto e letras brancas quando o mouse estiver em cima deles.

c) Adicione o padding de 2px e e mude a cor da fonte para azul de todos os elementos da classe "menu" que sejam irmãos do elemento com id "principal".

d) Mude a cor da fonte para branco de todos os elementos da classe "interno" que são filhos de uma \<div\>, sendo que as divs devem estar contidas em elementos da classe "principal".

