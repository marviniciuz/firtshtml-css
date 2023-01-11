# Livros para aprender HTML5 e CSS3


## Mozilla Developer:
[HTML: Linguagem de Marcação de Hipertexto](https://developer.mozilla.org/pt-BR/docs/Web/HTML)

[CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

[HTML: tudo que você precisa saber sobre o assunto!](https://blog.betrybe.com/html/)

[CSS: o que é, guia sobre como usar e vantagens!](https://blog.betrybe.com/css/)

## Livros de Front-end (Casa do Codigo):

[Livros de Front-end / HTML e CSS](https://www.casadocodigo.com.br/collections/front-end-html-e-css)

## Livros:

* HTML 5. Entendendo E Executando 
* HTML5 e CSS3: guia prático e visual 
* Fundamentos de HTML5 e CSS3 
* Use a cabeça! HTML e CSS

## Como é o funcionamento do HTTP?

HTTP é um protocolo baseado em texto sem conexão. Isso significa que as pessoas que acessam o site da sua empresa enviam solicitações a servidores que as exibem na forma do seu site em formato de texto, imagens, e outros tipos de mídia. Depois que a solicitação é atendida por um servidor, a conexão entre o usuário e o servidor é desconectada.

Uma nova conexão deve ser feita para cada solicitação, isto é, cada vez que alguém acessa o seu site. Em suma, quando alguém digita a URL do seu site em um navegador, é isto que acontece:

* se a URL pertencer a um domínio próprio, o navegador primeiro se conecta a um servidor e recuperará o endereço IP correspondente ao servidor;

* o navegador se conecta ao servidor e envia uma solicitação HTTP para a página da web desejada (que, neste exemplo, é o seu site);

* o servidor recebe a solicitação e verifica a página desejada. Se a página existir, o servidor a mostrará. Se o servidor não conseguir encontrar a página solicitada, ele enviará uma mensagem de erro HTTP 404, ou seja, página não encontrada;

* o navegador, então, recebe a página de volta e a conexão é fechada;
caso a página exista (e é isso que se espera), o navegador a analisa e procura outros elementos necessários para concluir a sua exibição, o que inclui seus textos, imagens e afins;

* para cada um desses elementos, o navegador faz conexões adicionais e solicitações HTTP para o servidor para cada elemento;

* quando o navegador terminar de carregar todos os elementos, a página será carregada na janela do navegador.

## Dominio e Hospedagem

exemplo de URL:

www.github.com/marviniciuz

* www = sub dominio;
* github.com = dominio;
* .com = TLD;
* marviniciuz = caminho;

## Tags em HTML:
Como adicionar um titulo em html: 

~~~html
<h1>
    ola mundo 
        </h1>
~~~~
Como adicionar um paragrafo em html:
~~~html
<p>
    ola mundo 
            </p>
~~~

## Estilização em CSS:

~~~css
h1 {
  color:green; 
}
~~~

O css trabalha com seletores, ou seja ele direciona ou seleciona os elementos ou tags html em que ele quer estilizar, com isso a cada seletor você estiliza um elemento.

ou seja na criamos o o titulo que estava na h1 e informamos ou selecionamos ela no arquivo.css para que seja selecionado e estilizado o titulo que esta na tag h1.

Todo arquivo css e composto por seletores que no caso e tudo e o:
~~~css
h1 {
  color:green; 
  font-family: arial;
}
~~~

* font-family: arial; (declaração)
* color: (e uma propriedade)
* green; (e um valor)
