<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<!-- 2020-02-21 sex 19:57 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#org8690981">1. Trocando imagens ao apertar um botão</a></li>
<li><a href="#org01bc803">2. Podemos usar os ícones do Material Design</a></li>
<li><a href="#org2643392">3. Instalando plugin</a></li>
</ul>
</div>
</div>

<div id="outline-container-org8690981" class="outline-2">
<h2 id="org8690981"><span class="section-number-2">1</span> Trocando imagens ao apertar um botão</h2>
<div class="outline-text-2" id="text-1">
<p>
Você deve baixar duas imagens de WIFI ligado e desligado. Deve salvá-las na pasta <b>img</b> dentro de <b>www</b>.
</p>

<p>
E usar os códigos à seguir:
</p>

<pre class="example">
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Teste de figura&lt;/title&gt;
    &lt;script src="js/programa.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;img src="img/wifion.png" alt="" id="imagem" width="100"&gt;
    &lt;input type="button" id="botao" value="Liga/Desliga"&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>

<p>
E colocar o código abaixo na pasta <b>js</b> com nome <b>programa.js</b>:
</p>

<pre class="example">
var ligado = true;

function troca() {
    var imagem = document.getElementById("imagem");

    if(ligado == true) {
        ligado = false;
        imagem.src = "img/wifioff.png";
    } else {
        ligado = true;
        imagem.src = "img/wifion.png";
    }    
}

window.onload = function() {
    var botao = document.getElementById("botao");
    botao.addEventListener("click", troca);
}
</pre>
</div>
</div>

<div id="outline-container-org01bc803" class="outline-2">
<h2 id="org01bc803"><span class="section-number-2">2</span> Podemos usar os ícones do Material Design</h2>
<div class="outline-text-2" id="text-2">
<p>
Utilize o CSS abaixo na sua página:
</p>

<pre class="example">
&lt;link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"&gt;
</pre>

<p>
Disponível em: <a href="http://google.github.io/material-design-icons/">http://google.github.io/material-design-icons/</a>
</p>

<p>
Em seguida escolha um ícone em:
</p>

<p>
<a href="https://material.io/resources/icons/?icon=wifi_off&amp;style=baseline">https://material.io/resources/icons/?icon=wifi_off&amp;style=baseline</a>
</p>

<p>
Clique em um ícone desejado e do lado esquerdo aparece como inserí-lo na página:
</p>

<pre class="example">
&lt;i class="material-icons"&gt;
wifi_off
&lt;/i&gt;
</pre>

<p>
No caso anterior, basta alterar o innerHTML de &lt;i&gt;, <b>wifi_off</b> para <b>wifi</b> que o ícone muda.
</p>

<p>
Podemos criar uma função que altera o ícone assim:
</p>

<pre class="example">
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Sinal&lt;/title&gt;
    &lt;link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"&gt;
      &lt;style&gt;
          i {
              font-size: 500%;
          }
    &lt;/style&gt;
    &lt;script&gt;
    var ligado = true;
    function muda() {
        var item = document.getElementsByTagName("i");
        
        if(ligado) {
            item[0].innerHTML = "wifi_off";
            ligado = false;
        } else {
            item[0].innerHTML = "wifi"
            ligado = true;
        }
    }
        
    &lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;i class="material-icons"&gt;
wifi
&lt;/i&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>

<p>
Em seguida podemos inserir um botão que faz a alteração de wifi ligado para wifi desligado e vice-versa:
</p>

<pre class="example">
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Sinal&lt;/title&gt;
    &lt;link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"&gt;
      &lt;style&gt;
          i {
              font-size: 500%;
          }
    &lt;/style&gt;
    &lt;script&gt;
    var ligado = true;
    function muda() {
        var item = document.getElementsByTagName("i");
        
        if(ligado) {
            item[0].innerHTML = "wifi_off";
            ligado = false;
        } else {
            item[0].innerHTML = "wifi"
            ligado = true;
        }
    }
        
setInterval(muda, 2000);
    &lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;i class="material-icons"&gt;
wifi
&lt;/i&gt;
&lt;input type="button" id="botao" value="Lig/Des"&gt;
&lt;/body&gt;
&lt;/html&gt;
#+BEGIN_EXAMPLE

O funcionamento desse botão deve ficar, quando acontecer o evento "click" a função muda() é executada.

Para isso adicionamos o código abaixo ao script:

#+BEGIN_EXAMPLE
function inicio() {
        var botao = document.getElementById("botao");
        
        botao.addEventListener("click", muda);
    }
        
window.onload = function() {
    inicio();
}
</pre>

<p>
Podemos também de tempos em tempos executar a função muda(), para isso utilizamos a função setInterval().
</p>

<p>
Alterando o código do script para: 
</p>

<pre class="example">
&lt;script&gt;
    var ligado = true;
    function muda() {
        var item = document.getElementsByTagName("i");
        
        if(ligado) {
            item[0].innerHTML = "wifi_off";
            ligado = false;
        } else {
            item[0].innerHTML = "wifi"
            ligado = true;
        }
    }
        
setInterval(muda, 2000);
    &lt;/script&gt;
</pre>
</div>
</div>

<div id="outline-container-org2643392" class="outline-2">
<h2 id="org2643392"><span class="section-number-2">3</span> Instalando plugin</h2>
<div class="outline-text-2" id="text-3">
<p>
Podemos verificar a conexão com a Internet usando o plugin cordova-plugin-network-information.
</p>

<p>
<a href="https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-network-information/index.html">https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-network-information/index.html</a>
</p>

<p>
Para instalar use o comando:
</p>

<pre class="example">
cordova plugin add cordova-plugin-network-information
</pre>

<p>
Podemos usar a função dada como exemplo para determinar o tipo de conexão:
</p>

<pre class="example">
function verificaConexao() {
    var networkState = navigator.connection.type;

    var states = {};
    states[Connection.UNKNOWN]  = 'Conexão desconhecida';
    states[Connection.ETHERNET] = 'Conexão ethernet';
    states[Connection.WIFI]     = 'Conexão WiFi';
    states[Connection.CELL_2G]  = 'Conexão 2G';
    states[Connection.CELL_3G]  = 'Conexão 3G';
    states[Connection.CELL_4G]  = 'Conexão 4G';
    states[Connection.CELL]     = 'Conexão genérica';
    states[Connection.NONE]     = 'Sem conexão';

    alert('conexão type: ' + states[networkState]);
}

verificaConexao();
</pre>

<p>
Podemos adicionar EventListener para o caso da internet cair:
</p>

<pre class="example">
document.addEventListener("offline", caiu, false);

function caiu() {
    // o que fazer quando cair
}
</pre>

<p>
E também ouvir quando a internet volta:
</p>

<pre class="example">
document.addEventListener("online", voltou, false);
</pre>

<p>
Resolver:
</p>

<pre class="example">
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
   &lt;meta http-equiv="Content-Security-Policy" content="default-src 'self' data: gap: https://ssl.gstatic.com 'unsafe-eval'; style-src 'self' 'unsafe-inline'; media-src *; img-src 'self' data: content:;"&gt;
        &lt;meta name="format-detection" content="telephone=no"&gt;
        &lt;meta name="msapplication-tap-highlight" content="no"&gt;
        &lt;meta name="viewport" content="initial-scale=1, width=device-width, viewport-fit=cover"&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Sinal&lt;/title&gt;
    &lt;link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"&gt;
      &lt;style&gt;
          i {
              font-size: 500%;
          }
    &lt;/style&gt;
    &lt;script&gt;
    var ligado = true;
    function muda(texto) {
        var item = document.getElementsByTagName("i");
        
        if(ligado) {
            item[0].innerHTML = "wifi_off";
            ligado = false;
        } else {
            item[0].innerHTML = "wifi"
            ligado = true;
        }
        
        var pa = document.getElementById("para");
        pa.innerHTML = texto;
    }
        
window.onload = function() {
    setInterval(verificaConexao, 2000);
}
        

        
    function verificaConexao() {
    var networkState = navigator.connection.type;

    var states = {};
    states[Connection.UNKNOWN]  = 'Conexão desconhecida';
    states[Connection.ETHERNET] = 'Conexão ethernet';
    states[Connection.WIFI]     = 'Conexão WiFi';
    states[Connection.CELL_2G]  = 'Conexão 2G';
    states[Connection.CELL_3G]  = 'Conexão 3G';
    states[Connection.CELL_4G]  = 'Conexão 4G';
    states[Connection.CELL]     = 'Conexão genérica';
    states[Connection.NONE]     = 'Sem conexão';

    muda(states[networkState]);
}

    &lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;i class="material-icons"&gt;
wifi
&lt;/i&gt;
&lt;input type="button" id="botao" value="Lig/Des"&gt;
&lt;p id="para"&gt;&lt;/p&gt;
&lt;script type="text/javascript" src="cordova.js"&gt;&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2020-02-21 sex 19:57</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>
