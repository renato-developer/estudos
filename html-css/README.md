# HTML5 e CSS3
 * Resumo simplista de desenvolvimento web com HTML5 e CSS3.

---
## História da Internet
* **1960** - ARPANET precursora da Internet, desenvolvida pela ARPA do Departamento de Defesa dos EUA.

* Conectou computadores em várias instituições de pesquisa para troca de informações.

* **1972** - Ray Tomlinson criou primeiro programa de e-mail.

* Permitindo usuários enviar mensagens em diferentes computadores.

* **1980** - TCP/IP tornou-se padrão para redes.

* Permitindo diferentes redes se interconectassem e formassem a base da Internet.

* **1983** - DNS foi introduzido.
 
* Permitindo o uso de nomes de domínio legíveis em vez de endereços IP numéricos.

* **1989** - WWW foi criado por Tim Berners-Lee.

* Com esse sistema de hipertexto Tim criou o primeiro navegador e servidor web.

* **1990** - Web ganhou popularidade.
 
* Levando à criação de sites, mecanismos de busca e proliferação do conteúdo online.

* **2000** - Frenesi de investimentos especulativos em empresas baseadas na Internet estourou.

* Levando a queda nos preços das ações e fechamento de muitas empresas pontocom.

* **2003** - O surgimento de plataformas de mídia social.

* Transformando a forma como as pessoas interagem e compartilham informações online com conteúdos gerado pelo usuário.

* **2010** - Adoção generalizada de smartphones.

* Alimentando o crescimento da internet móvel e expansão das conexões banda larga.

* **2020** - Inteligência artificial, blockchain, realidade virtual, etc.

* Ainda mostraram sua Relevância.

---
## Como a Internet funciona
* Empresas fornecem Internet através de infraestrutura física.

* Dispositivos são conectados por meio de cabos físicos ou conexões sem fio.

* Dispositivos conectados à Internet recebem um IP exclusivo, que permite se localizarem e se comunicarem.

* Um conjunto de protocolos governam como os dados são transmitidos e recebidos.

* Dados transmitidos são divididos em unidades menores chamadas pacotes junto com informações do IP de origem e destino.

* Roteadores e Switches examinam o IP dos pacotes e com algoritmos definem o melhor caminho para os dados.

* Quando os pacotes chegam, são reagrupados pelo dispositivo receptor, se o pacote for corrompido, poderá ser retransmitido.

* Firewalls controlam entrada e saída de dados, aplicando políticas de segurança para evitar atividades maliciosas.

---
## Domínio
* Identifica e localiza recursos, como sites, servidores de e-mail e outros serviços online.

* Endereço legível por humanos.

* Representa uma entidade exclusiva na World Wide Web.

* Na URL "www.example.com/renato-machado":
  * **www** sub-domínio, não é parte do próprio domínio.
  * **exemplo** SLD, nome do domínio.
  * **.com** TLD, extensão do domínio.
  * **renato-machado** caminho.

---
## Hospedagem
 * Serviço de armazenamento com recursos de servidor tornando os sites acessíveis na Internet.

---
## Requisitos e Custos do Site
* **Domínio**
  * Nome único.
  * TLD Adequado.
  * Pago Anualmente R$ 5 – R$ 50 + renovação R$ 50 – R$ 200.

* **Hospedagem**
  * Disponibiliza espaço de armazenamento e Recursos Web.
  * Pago Mensalmente R$ 7 – R$ 800.

---
## HTML5
* Linguagem de marcação usada para estruturar e apresentar conteúdo na World Wide Web.

---
## CSS 
* Usada para criar o estilo visual de documentos HTML e XML.

---
## JavaScript
* Linguagem de programação interpretada de alto nível, adiciona interatividade e comportamento dinâmico a sites.

* Executado diretamente no navegador Web no lado do cliente.

* Considerado linguagem de script porque não requer compilação explícita antes da execução.

---
## Front-End
* Trabalha com Client-Side, iterface do usuário, elementos visuais e interativos da pagina web.

---
## Back-End
* Trabalha com Server-Side, armazena dados, lógica de negócios e comunicação com outros sistemas.

* Processa solicitações do front-end, interage com bancos de dados e gerar conteúdo dinâmico de volta ao front-end.

---
## Full Stack
* Trabalha com desenvolvimento front-end e back-end.

---
## Ferramentas Básicas
* Google Crome

* Visual Studio Code

* GitHub Desktop

* GIMP

---
## Configuração Visual Studio Code

**Quebra de linha**

`CTRL` + `,` `Editor:Word Wrap` `on`

---
**Tamanho de Fonte**

`CTRL` + `,` `Editor:Font Size` `20`

---
**Tema**

`CTRL` + `,` `Workbench:Color Theme` `Dark Modern`

---
**Salvar Automático**

`File` `Auto Save`

---
**Extensão - HTML em tempo real**

Live Server.

---
# Códigos HTML

**Código base**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

---
**Diz que é um documento em HTML5**

`<!DOCTYPE html>`

---
**Indica o idioma do site**

`<html lang="`en`">`

---
**Todo o Site**

`<html> </html>`

---
**Toda a configuração do site**

`<head> </head>`

---
**Todo o conteúdo do site**

`<body> </body>`

---
**Habilita o conjunto de caracteres com acentuação**

`<meta charset="UTF-8">`

---
**Diz que o site vai ocupar todo o espaço da tela**

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

---
**Título do Site**

`<title> </title>`

---
**Título do Artigo**

`<h1> </h1>`

---
 **Subtítulo**

`<h2> </h2>` até `<h6> </h6>`

---
**Parágrafo**

`<p> </p>`

---
**Linha Horizontal**

`<hr>`

---
**Quebra de linha**

`<br>`

---
**Mostra a tag <**

`&lt;`

---
**Mostra a tag >**

`&gt;`

---
**Transforma em Comentário**

`<!--`Texto`-->`

---
**Adiciona Imagem**

`<img src=`"local-do-arquivo" `alt=`"texto-alternativo"`>`

---
**Adiciona Favicon**

`<link rel="shortcut icon" href=`"favicon.ico" `type="image/x-icon">`

---
**Negrito**

`<strong> </strong>`

---
**Itálico**

`<em> </em>`

---
**Marcador de Texto**

`<mark> </mark>`

---
**Letras Pequenas**

`<small> </small>`

---
**Texto Deletado (Riscado)**

`<del> </del>`

---
**Texto Inserido (Sublinhado)**

`<ins> <ins>`

---
**Texto Sobrescrito**

`<sup> </sup>`

---
**Texto Subscrito**

`<sub> </sub>`

---
**Fonte Monoespaçada**

`<code> </code>`

---
**Texto Indentado**

`<pre> </pre>`

---
**Citação Simples (Coloca entre "")**

`<q> </q>`

---
**Citação Completa**

`<blockquote cite="`https://`"> </blockquote>`

---
**Mostra o significado da abreviação**

`<abbr title="`Sigla`">`Significado`</abbr>`

---
**Lista Ordenada**

```
<ol type="1" start="1">
<li>
<li>
<li>
</ol>
```

`type=""` Pode ser (1, A, a, I, i).

---
**Lista não Ordenada**

```
<ul type="disc">
<li>
<li>
<li>
</ul>
```

`type=""` Pode ser (disc, circle, square).

---
**Lista de Definições**

`<dl>`

`<dt>`O que vai ser definido`</dt>` 

`<dd>`Definição`</dd>`

`</dl>`

---
**Link Interno**

`<a href="`https://renato-machado-developer.github.io/ `" rel="next" target="_self">` Indica que é a próxima página (Mesmo site).

`<a href="`https://renato-machado-developer.github.io/ `" rel="prev" target="_self">` Indica que é a página anterior (Mesmo site).

---
**Link Externo**

`<a href="`https://renato-machado-developer.github.io/ `" target="_blank"` `rel="external">` Indica que é a página de outro site.

`<p>`Esta página é um oferecimento de `<a href="`https://www.hostnet.com.br/ `" target="_blank"` `rel="nofollow">` `Hostnet</a></p>` Indica para o mecanismo de busca não perpetuar o link.

---
**Download**

`<a href="`livro/meulivro.zip`" download="`meulivro.zip`" type="application/zip">`Livro compactado em ZIP`</a>`

---
**Imagens Dinâmica**

```
<picture>
    <source media="(max-width: 750px)" srcset="imagens/foto-p.png">
    <source media="(max-width: 1050px)" srcset="imagens/foto-m.png">
    <img src="imagens/foto-g.png" alt="imagem flexível">
</picture>
```

---
**Colocando Áudio**

```
<audio preload="metadata" controls>
    <source src="midia/big-river.mp3" type="audio/mpeg">
    <source src="midia/big-river.ogg" type="audio/ogg">
    <source src="midia/big-river.wav" type="audio/wav">
    <p>Infelizmente seu navegador não consegue reproduzir áudio. <a href="midia/big-river.mp3">Clique aqui para baixar o arquivo MP3.</a></p>
</audio>
```

---
**Colocando Vídeo no próprio servidor**
 * Formatos - m4v, mp4, ogv, webm.

```
<video width="560" poster="imagens/limoes-capa.png" controls>
    <source src="midia/meu-video.mp4" type="video/mp4">
    <source src="midia/meu-video.m4v" type="video/mp4">
    <source src="midia/meu-video.webm" type="video/webm">
    <source src="midia/meu-video.ogv" type="video/ogg">
    <p>Seu navegador não tem compatibilidade com reprodução de vídeos</p>
</video>
```

---
**Colocando Vídeo Externo (YouTube)**

`Compartilhar` `Incorporar` `Copiar`

```
<h1>Inserindo vídeos do YouTube</h1>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6iw6GmoX3Lc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```

---
## Atalhos

**Colocando abertura e fechamento de tag, no texto selecionado**

`CTRL` + `SHIFT` + `P` `Emment Wrap with Abbreviation` + TAG

---
**Aumenta Tabulação**

Seleciona o texto e `TAB`

---
**Diminui Tabulação**

Selecione o texto  e `SHIFT` + `TAB`

---
**Edite várias linhas**

`Clique na linha` + `Segure ALT` + `Clique em outra linha`.

---
## Dicas Gerais

**Voltar para pastas anteriores**

`../`

**Procurar Local do Arquivo**

`CTRL` + `Espaço` entre "" o src.

---
## Símbolos e Emoticons

**Marca registrada**

`&reg;`

---
**Marca registrada em inglês**

`&trade;`
 
---
**Direito Autoral**

`&copy;`
 
---
**Delta Minúsculo**

`&delta;`
 
---
**Delta Maiúsculo**

`&Delta;`
 
---
**Seta para cima**

`&uparrow;`
 
---
**Seta para cima simplificado**

`&uarr;`

---
**Coloca um Emoji**

`&#x` `00000`

---
## Moeda

**União Européia (Euro)**

`&euro;`

---
**Reino Unido (Libra Esterlina)**

`&pound;`

---
**Japão (Iene)**

`&yen;`

---
**Estados Unidos da América (Dólar)**

`&cent;`

---
# CSS

**Colocando o CSS externo na página**

`<link rel="stylesheet" href="`nome-arquivo.css `">`

---
**Regra de Acentuação**

`@charset "UTF-8";`

---
**Colocando fonte externas**

```
@font-face {
            font-family: 'Love';
            src: url(fonts/love\ story\ ttf.ttf) format(truetype);
}
```

---
**Adicionar Variável de Cor/Fonte**

```
:root {
    --Picton Blue: #39A4DD;
    --Purpureus: #9A57B4;

    --fonte-padrao: Arial, Verdana, Helvetica, sans-serif;
    --fonte-Ubuntu-Light: 'Ubuntu Light', Times, sans-serif;
}
```

---
**Configuração Geral**

```
* {

}
```

---
**Tamanho Mínimo da Página**
`min-width:` `320px` `;`

---
**Tamanho Máximo da Página**
`max-width:` `1024px` `;`

---
**Tamanho Fixo do conteúdo em Tela cheia**
`margin:` `auto` `;`

---
**Cor de Fundo**

`background-color:` `lightcoral` `;`

---
**Cor de fundo em Degrade**

`background-image: linear-gradient` `(to top, #4FFFDC, #3FCCB0, #3D8577);`

---
**Colocando imagem de fundo**

`background-image:` `url(imagem.jpg)` `;`

---
**Posição da imagem de fundo**

`background-position:` `center center` `;`

---
**Não repetir imagem de fundo**

`background-repeat:` `no-repeat` `;`

---
**Tamanho da imagem de fundo**

`background-size:` `cover` `;`

---
**Imagem Fixada no fundo**

`background-attachment:` `fixed` `;`

---
**Fonte do Texto**

`font-family:` `Arial, Helvetica, sans-serif` `;`

---
**Tamanho da Fonte do Texto**

`font-size:` `20px` `;`

---
**Cor da Fonte**

`color:` `darkblue` `;`

---
**Alinhamento do texto**

`text-align:` `left` `;`

* left, center, right, justify

---
**Espaço entre linhas**

`line-height:` `1em` `;`

---
**Espaço no começo do parágrafo**

`text-indent:` `24px` `;`

---
**Altura 100%**

`height:` `100%` `;`

---
**Largura**

`width:` `600px` `;`

---
**Acolchoamento**

`padding:` `10px` `;`

---
**Centralizar**

`margin:` `auto` `;`

---
**Arrendodando Bordas**

`border-radius:` `10px` `;`

---
**Sombra na Caixa de Texto**

`box-shadow:` `5px` `5px` `rgba(136, 109, 93, 0.616)` `;`

* Parâmetros, 5px para o lado, 5px para baixo, espalhamento, transparência.

---
**Sombra no Texto**

`text-shadow:` `1px` `1px` `2px` `rgba(129, 77, 5, 0, 0.726)` `;`

* Parâmetros, 5px para o lado, 5px para baixo, espalhamento, transparência.

---
**Peso da Fonte**

`font-weight:` `normal` `;`

* lighter, normal, bold, bolder

* 100 - 900

---
**Estilo da Fonte**

`fonte-style:` `italic` `;`

---
**Decorando o Texto**

`text-decoration:` `underline` `;`

---
**Modificando Marcador da Lista**

`list-style-type:` `'\2714\00A0\00A0'` `;`

---
**Posição da Lista**

`list-style-position:` `inside` `;`

---
**Dividir lista em colunas**

`columns:` `2` `;`

---
## Aninhamento

**Caixa Contém**

* height - Altura

* width - Largura

* border - Borda

* padding - Espaço interno

* margin - Espaço Externo

* outline - Contorno

---
**Largura da Borda**

`border-width:` `10px` `;`

---
**Estilo da Borda**

`border-style:` `solid` `;`

---
**Cor da Borda**

`border-color:` `darkgray` `;`
            
---
**Altura do Preenchimento**

`padding-top:` `10px` `;`

---
**Largura Direita do Preenchimento**

`padding-right:` `10px` `;`

---
**Largura de Baixo do Preenchimento**

`padding-bottom:` `10px` `;`

---
**Largura Esquerda do Preenchimento**
            
`padding-left:` `10px` `;`

---
**Margem de Cima**

`margin-top:` `10px` `;`

---
**Margem da Direita**

`margin-right:` `10px` `;`

---
**Margem de Baixo**

`margin-bottom:` `10px` `;`

---
**Margem da Esquerda**

`margin-left:` `10px` `;`

---
**Centralizar a Caixa**

`margin: auto;`

---
**Largura do Contorno**

`outline-width:` `5px` `;`

---
**Estilo do Contorno**

`outline-style:` `dashed` `;`

---
**Cor do Contorno**

`outline-color:` `salmon` `;`

---
**Tempo de Trasição**

`transitioni-duration:` `0.5` `;`

---
**Símbolos nas CSS**

```
 # = id
 . = class
 : = pseudo-class
 :: = pseudo-element
 > = children
```

---
**id**

`<h1 id="`nome`">`Texto`</h1>`

```
h1#nome {

}
```

---
**class**

`<h1 class="`nome`">`Texto`</h1>` 

```
.nome {

}
```

---
## pseudo-classes

**Passar o mouse, faz uma ação**

```
div:hover {

}
```

---
**Parâmetro para Links Visitados**

```
div:visited {

}
```

---
**Parâmetro quando Clicado**

```
div:active {

}
```

---
**Mostra o Parágrafo Escondido**

```
div:hover > p {
    display: block;
}
```

---
**children**

* Esconde o parágrafo

```
div > p {
    display: none;
}
```

---
**pseudo-element**

* Mostrar algo antes.

```
.especial::before {
    content: 'Before ';
}
```

---
* Mostrar algo depois.

```
.especial::after {
    content: ' After';
}
```

---
**Vídeo Responsivo**

```
div.video {
    margin: 0px -20px 30px -20px;
    padding: 20px
    padding-bottom: 58%;
    position: relative;
}
```

```
div.video > iframe {
    position: absolute;
    top: 5%;
    left: 5%;
    width: 90%;
    height: 90%;
}
```

---

## Simplificando (shorthand)

**font**

```
font-family: Arial, Helvetica, sans-serif;
font-weight: bolder;
font-size: 3em;
font-style: italic;
```

* font-style -> font-weight -> font-size -> font-family

`font: italic bolder 3em Arial, Helvetica, sans-serif;`

---
**border**

```
border-width: 10px;
border-style: solid;
border-color: darkgray;
```

`border: 10px solid darkgray;`

---
**Borda Personalizada**

```
border-image-source: url("borda.png");
border-image-slice: 38;
border-image-repeat: repeat;
```

`border-image: url('borda.png') 27 repeat;`

---
**padding**

```
padding-top: 10px;
padding-right: 10px;
padding-bottom: 10px;
padding-left: 10px;
```

`padding: 10px 10px 10px 10px;`

---
**margin**

```
margin-top: 20px;
margin-right: 20px;
margin-bottom: 40px;
margin-left: 20px;
```

`margin: 20px auto 40px auto;`

---
**outline**

```
outline-width: 5px;
outline-style: dashed;
outline-color: salmon;
```

`outline: 5px dashed salmon;`

---
**Imagem de Fundo**

```
body {
    height: 100vh;
    background-color: black;
    background-image: url(img/wallpaper003.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}
```

* color > image > position > repeat > [size] > attachment

`background: black url(img/wallpaper003.jpg) center center no-repeat fixed;`

`background-size: cover;`

---
**Tipos de format() nas Fontes**

* opentype (otf)

* truetype (ttf)

* embedded-opentype

* truetype-aat (Apple Advanced Typography)

* svg

---
**Tipografia**

* Tipos de escrita, emoção da escrita.

* Letra - Glifo.

* Conjunto de Glifos - Fonte.

* Família Tipográfica - Diferentes formas de representar o mesmo Glifo.

---
**Categoria de Fonte:**

* Serifadas - Possuem Serifa.

* Sans-serif - Não possue Serifa.

* Monoespaçadas - Todas as letras tem a mesmo largura.

* Handwriting - Simula letras Escrita a Mão.

* Display - Comemorativas, não tem nenhuma características, nenhuma regra.

**Ideal para sites - Sans-serif.**

---
## Medidas de Fonte

**Medidas Absolutas**

* cm, mm, in, px, pt, pc

---
**Medidas Relativas**

* em, ex, rem, vw, vh, %

---
**Recomendado** 

* px, em

* 16px , 1em

---
**Cores**

* rgba - Cores rgb com transparência

* Primárias - Amarelo,Vermelho, Azul.

* Secundárias - Laranja, Violeta, Verde.

* Terciáras - Amarelo-Esverdeado, Amarelo-Alaranjado, Vermelho-Alaranjado, Vermelho-Arroxeado, Azul-Arroxeado, Azul-Esverdeado, Amarelo-Esverdeado.

* Cores Quentes - Amarelo, Amarelo-Alaranjado, Laranja, Vermelho-Alaranjado, Vermelho, Vermelho-Arroxeado.

* Cores Frias - Violeta, Azul-Arroxeado, Azul, Azul-Esverdeado, Verde, Amarelo-Esverdeado.

* Paleta de Cores - Parti de uma cor principal.

* Paleta de Cores - 3 a 5 cores. Desconsidera preto e branco.

---
## Lista de exercícios
* [001 - Código Base.]()

* [002 - Parágrafos, Quebras de Linha, Símbolos, Emoji]()

* [003 - Colocar Imagem]()

* [004 - Colocar Favicon]()

* [005 - Hierarquia de Títulos]()

* [006 - Negrito, Itálico, Texto Marcado, Pequeno, Deletado, Inserido, Sobrescrito e Subscrito.]()

* [007 - Codigo, Citação, Abreviação]()

* [008 - Lista Ordenada, Não Ordenada, Misturada, de Definições.]()

* [009 - Usando Links externos]()

* [010 - Imagem Dinâmica e Reproduzir Áudio]()

* [011 - Vídeos Local e Externo]()

* [012 - CSS Externo]()

* [013 - Representação por Nomes, Hexadecimais, RGB, HSL, Transparência e Degradê]()

* [014 - Fontes em CSS]()

* [015 - Fontes com Google Fonts, Externas e Alinhamento]()

* [016 - Seletores personalizados em CSS]()

* [017 - Hover, Links, Pseudo-Classes]()

* [018 - Modelo de Caixa, Grouping Tags]()

* []()

* []()

* []()

* []()

* []()

* []()

* []()

* []()

* []()

* []()

* []()

* []()
---
## Glossário

* **ARPAnet** Advanced Research Projects Agency Network (Rede da Agência de Pesquisas em Projetos Avançados).

* **Blockchain** mecanismo de banco de dados que permite o compartilhamento transparente de informações na rede.

* **CSS** Cascading Style Sheets (Folhas de Estilo em Cascata).

* **Client-Side** Lado do Cliente  

* **DNS** Domain Name System (Sistema de nomes de domínio).

* **DNS** Diretório que traduz nomes de domínios para IP's correspondentes.

* **Firewalls** examina pacotes de dados que passam pela rede e decide permitir ou bloquear com base em regras predefinidas.

* **Full-Stack** Pilha Completa.

* **HTML**  Hypertext Markup Language (Linguagem de Marcação de Hipertexto).

* **IP** Internet Protocol (Protocolo de Internet).

* **IP** endereça e roteá pacotes de dados pela Internet.

* **Linguagem de programação de Alto Nível** Projetada para fácil leitura, escrita e entendimento.

* **Linguagem de programação Interpretada** Lê e executa o código linha por linha, traduzindo-o em instruções de máquina em tempo real.

* **Server-Side** Lado do Servidor

* **SLD** Second Level Domain (Domínio de Segundo Nível).

* **SLD** é a parte do nome de domínio.

* **TCP** Transmission Control Protocol (Protocolo de Controle de Transmissão).

* **TCP** faz comunicação confiável, controle de fluxo, recuperação de erros, garantindo integridade e entrega dos dados.

* **TCP/IP** conjunto de protocolos que formam a comunicação e transferência de dados na Internet.

* **TLD** Top-Level Domain (Domínio de Nível Superior).

* **TLD** é a extensão do domínio.

* **URL** Uniform Resource Locator (Localizador Uniforme de Recursos).

* **URL** Endereço web, texto digitado na barra do navegador para acessar determinada página ou serviço.

* **WWW** World Wide Web (Rede Mundial de Computadores).

* **WWW** sistema de documentos em hipermídia interligados e executados na Internet.

---
## Bibliografia

YouTube: [Curso em Vídeo](https://www.youtube.com/@CursoemVideo)

Professor: Gustavo Guanabara

Playlist: [Curso completo e atual de HTML5 e CSS3 - Módulo 1 de 5](https://www.youtube.com/watch?v=Ejkb_YpuHWs&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=1)

---
YouTube: [How Does the Internet Work ?](https://www.youtube.com/watch?v=TNQsmPf24go)

---
[ChatGPT](https://chat.openai.com/auth/login?next=/chat)

---