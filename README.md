# ht-page2

Obs de links:

Origem - http://meusite.com/paginas/bio.html

portfolio.html
/posts/html5-e-css3.html
//facebook.com

http://meusite.com/paginas/portfolio.html
http://meusite.com/posts/html5-e-css3.html
http://facebook.com

---------

<main>: conteúdo principal da página
<header>: cabeçalho da página ou de uma região dela
<footer>: mesma ideia da tag <header> para o rodapé
<aside>: conteúdo auxiliar ao conteúdo principal, como links relacionados ao conteúdo
<article>: conteúdo que, por si só, já tem um sentido completo, como um post de um blog ou uma notícia
<section>: parte/seção de uma página ou texto

---------

cor de link

<ul>
    <li>
        <a href="#">Link 1</a>
    </li>
</ul>

ul {
    color: pink;
}

ul li a {
    color: inherit;
}

---------

No momento, estamos usando o reset do Eric Meyer, mas existem várias alternativas. Uma também bastante famosa é o Normalize, criado por Nicolas Gallagher e Jonathan Neal.

---------

display : (inline, block e inline-block , none)

---------

position: relativo, relativo ao local de origim (a ele mesmo) - para a pagina ele mantem o fluxo
position: absolute, relativo a janela - sai do fluxo
position: fixed, fixo em relacao a tela - sai do fluxo