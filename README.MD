### . header###


# background
- para stilizar a cor do menu ex:#1d1e20

# FLEX
-Display flex para estilizar um link do lado do outro.

# space-between
- spaços longos entre eles
- justify-content:space-between

# padding:20px 
espaços laterais entre eles com os outros intens

# center
-alinhamento da logo ao centro
-align-items:center

# wrap
-para controlar quando a parte ficar pequena perto do outro
-flex-wrap:wrap

======================================================================
## .menu ##

display:flex; para ficar um do lado do outro
============================================

## .menu li ##
- criar uma area de contato maior para facilitar o crick obs: espaços 
separar os intens.

margin-lenf:10px;
==============================================
## menu li a ##

- display: block; esta colocando no  a
- padding:10px; e para dar espaços para cima e para baixo, no 
=============================================
## css flexbox ##
## Section Flexbox ##

-h1 vem intem com Section flexbox 
- text-align: center; para alinhar ao centro
- margin-top:100px; para deferenciar altura espasamento do link

fazer uma divisão com a dv.. poderia dividir com.. ul,e li tambem fica escolha
depois colocar uma class"flex"
- depois e colocar as imagens dentro das div..ajustar as imagens com... "height="300px" width="300px"
=============================================
## img ##
-img amenta no maximo 100% do container responsivas
max-width: 100%;
displey:block; elas pegam no maximo 100%
=======================================================

## displey flex ##
cada item um do lado do outros 

displey: flex
flex:wrap; dizendo que ele pode quebrar
-
==============================================
## .flex < div ##

- flex: 1 1 200px;
 - margin:10px; margens para os intens 
 ============================================
 ## .flex ##
 - display:flex;
 - max-width: 800px;
 - margin:0 auto;  obs: para alinhar ao centr
 - flex-wrap: wrap; 
==============================
## grid1 ##
- display: grid;
- grid-template-colummns:1fr 1fr 1fr 1fr; obs: ou pode fazer desse jeito --- repeat(3, 1fr);
- max-width: 800px; para segurar esse conteiner 
- margin: 0 auto; para centralizar os conteudos
- grid-gap: 20px; para dar espasamento entre os grides distaciamento dos grides 

- as tres primeiras noticia querendo elas mais alargadas, grande. 
E pode ter uma class= ter uma class especificas para as menores, ou pode utilizar direto com selector css.

- grid > div:nth-child(1); pode se colocar os numeros ex: 2,3,4 ou pode tambem   n + 5 ele colore todos os itens do grid1
- backgroud:blue;
- displey;grid;  vou dividir uma parte image e outra texto.
- grid-template-colummns: 1fr 1fr; para fazer as divisão entre os grides.
- grid-gap: 10px;
- align-items: center; alinhamento do itens ao centro, os textos alinhado com minhas imagens.
==============================================================================
## anuncio ##

- anuncio esteja na primeira coluna 
- grid-colummns:1;

- quero que ela esteja da linha 2, a linha 5 obs: tem que contar as linhas no grid, para saber onde colocar elas.
- grid-row: 2 / 5 para fazer as divisão.
- displey:block;

 - parte responsivas
 - 

   @media(max-width:600px) {
       .grid1 {
        grid-template-columns:repeat(2, 1fr)
       }
       .Grid1 > div:nth-child(n +4) {
        display:block;
       }
       .Grid1 > div.anuncio {
        grid-template-columns: auto;
        grid-row: auto;
        order: -1;
       }
       ================================================