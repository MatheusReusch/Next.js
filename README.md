# Next.js é o presente e o futuro do Desenvolvimento Front-end?
<div align="center">
<img src="https://user-images.githubusercontent.com/91349862/159137224-8e1168ea-12da-4d59-84f1-8d7f38cce6f5.png" width="700px" />
</div>
<h1>Está interessado em entender o motivo da crescente popularização e utilização desse framework?</h1>
<div align="center">
<img src="https://user-images.githubusercontent.com/91349862/159137535-032f79e1-6bb6-431b-80b4-b2f3850f3678.png" width="700px" />
</div>
<h2>Se você está interessado em renderizar suas aplicações em React.js no lado servidor e conseguir maior escalabilidade para seus projetos, você precisa conhecer o framework Next.js!</h2>

<ins><h3>Qual a importância da renderização no lado servidor?</h3></ins>

Por padrão o React utiliza o Client-side Rendering, trazendo alguns prejuízos em relação ao Server-Side Rendering, principalmente quando avaliada a adequação da aplicação para os mecanismos de busca e SEO. Nesse contexto, a renderização do lado cliente acaba não permitindo uma avaliação e pesquisa concreta pelos mecanismos de busca, pois,enquanto a página está sendo renderizada, essas ferramentas de SEO a interpretam como um esqueleto de HTML vazio e sem conteúdo.

Nesse sentido, o Next.js surgiu para combinar o Client-Side Rendering e o Server-Side Rendering, apresentando-se como uma alternativa para a pré-renderização das páginas. Nesse sentido, é de extrema importância para inúmeras empresas que realmente haja uma correta adequação de seus websites com os padrões de busca dos navegadores.

Para isso, o Next.js renderiza o conteúdo no servidor e,após, devolve para o cliente. Todo esse processo é realizado com a utilização do Node.js para permitir a execução de código JavaScript no lado servidor.

<h3>Como o sistema de rotas baseado em arquivos (File-based Routing) funciona?</h3>

O Next.js utiliza o File-based Routing que surge para facilitar a criação de rotas (estáticas e dinâmicas) em aplicações React. 

Após executar o comando npx create-next-app, você poderá acessar a pasta src/pages e configurar suas rotas de acordo com o nome dos arquivos.

<div align="center">
<img src="https://user-images.githubusercontent.com/91349862/159138398-9123d5f7-5dd0-4c5a-ba15-97bcce5fa43d.PNG" width="500px" height="450px" />
</div>

Nesse caso, ocorre a criação de algumas rotas estáticas e dinâmicas como: '/' (index.js), '/login' (login.js), '/clientes' (clientes.js).

Os nomes de arquivos com colchetes "[]" representam as rotas dinâmicas.

Dessa forma, o Next.js dispensa a necessidade de instalação de ferramentas externas para a criação de rotas.

<h3>Como funciona a criação de rotas para API?</h3>

O Next.js também disponibliza a pasta src/pages/api para a criação de rotas de API's para o back-end.

Dessa maneira, a criação das rotas funciona da mesma maneira comentada no tópico anterior.

Portanto, caso seja criado um arquivo tempo.js dentro da pasta "src/pages/api", o caminho será "/api/tempo".

<h2>Como criar uma aplicação utilizando o Next.js</h2>

Para isso, basta executar o comando "npx create-next-app name-of-your-app" na pasta que deseja criar o projeto.

Após esperar alguns instantes para o projeto ser criado, você irá se deparar com a seguinte estrutura.

<div align="center">
<img src="https://user-images.githubusercontent.com/91349862/159138826-c9133e2b-3461-4aba-a65c-78007ea5593e.PNG" width="500px" height="450px" />
</div>

<h3>Pastas do Projeto:</h3>

<h4>Pages:</h4>

A pasta Pages é onde ficará toda a estrutura de código de sua aplicação (Componentes, Funções, Rotas e etc).

<h4>Public:</h4>

A pasta Public serve para armazenar alguns arquivos que serão úteis para o projeto (Imagens, Icons e etc).

