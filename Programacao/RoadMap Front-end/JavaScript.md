# O que é JavaScript
**JavaScript** é uma **linguagem de programação** que permite a você implementar itens complexos em páginas web — toda vez que uma página da web faz mais do que simplesmente mostrar a você informação estática — mostrando conteúdo que se atualiza em um intervalo de tempo, mapas interativos ou gráficos 2D/3D animados, etc.

<code> const btnmode = document.querySelector('.btnmode');
const main = document.querySelector('.main');
const submain = document.querySelector('.submain');
const baer = document.querySelector('.baer');
<code> btnmode.onclick = function(){
 this.classList.toggle('active')
 main.classList.toggle('active')
 submain.classList.toggle('active')
 baer.classList.toggle('active')

 }