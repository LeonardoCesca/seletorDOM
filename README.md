# seletorDOM
Exercicio para compreender um pouco sobre orientação a objetos em JavaScript


Criar seletor DOM (Document Object Model), similar ao JQuery. Este seletor deve ser um objeto, cujo o escopo é um elemento DOM da página e possui os seguintes métodos:
- find(seletor css): Retorna um objeto do tipo seletor DOM que busca o objeto pelo seletor css
- text() : Retorna o texto do elemento
- xpath(path) : Retorna um objeto do tipo seletor DOM que busca o objeto pelo xpath

Utilizar os métodos seguintes métodos DOM:
    - document.querySelector (Exemplo: document.querySelector("a").innerText)
    - document.evaluate (Exemplo: document.evaluate("//a", document).iterateNext().innerText)
    
Exemplo de uso:

Dado o seguinte código html:

<div>
   <h1>Hello World</h1>
     <span>Playing with javascript and DOM</span>
</div>

A exeução do objeto deverá ser capaz de reproduzir o seguinte:

(new SeletorDOM()).find("h1").text() => "Hello World"

(new SeletorDOM()).xpath("//div/span").text() => "Playing with javascript and DOM"


**Exercicio elaborado por: Henrique Vianna**
