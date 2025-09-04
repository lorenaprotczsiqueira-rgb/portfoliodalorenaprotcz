# portfoliodalorenaprotcz
<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Portfólio de Lorena Protcz</title>
<meta name="description" content="Portfólio simples feito em HTML puro.">
</head>
<body>
<!-- Conteúdo vem a seguir -->
</body>
</html>

<header>
<h1>Portfólio de Lorena</h1>
<p>Estudante de desenvolvimento web — HTML, CSS e JavaScript.</p>
<nav aria-label="Navegação principal">
<ul>
<li><a href="#sobre">Sobre</a></li>
<li><a href="#projetos">Projetos</a></li>
<li><a href="#contato">Contato</a></li>
</ul>
</nav>
</header>

<main>
<section id="sobre">
<h2>Sobre</h2>
<figure>
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fpt.vecteezy.com%2Ffotos-gratis%2Fespa%25C3%25A7o&psig=AOvVaw2hVYPHk5lP7Nj5mCItnjmR&ust=1757080227788000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCNi-upCgv48DFQAAAAAdAAAAABAE" alt="Retrato do Espaço.">
<figcaption>Foto ilustrativa do perfil</figcaption>
</figure>
<p>
Olá! Sou a Lorena e estou começando no desenvolvimento web.
Gosto de aprender criando projetos simples e práticos.
</p>
</section>

<section id="projetos">
<h2>Projetos</h2>
<article>
<h3>Lista de Tarefas (HTML)</h3>
<p>Projeto básico com listas e links.</p>
<ul>
<li>Lista não ordenada (bullet points)</li>
<li>Links externos com <code>target="_blank"</code></li>
<li>Estrutura semântica</li>
</ul>
<p>
Veja um exemplo de referência em
<a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML"
target="_blank" rel="noopener">
MDN Web Docs
</a>.
</p>
</article>
<article>
<h3>Página de Receitas</h3>
<p>Estruturação de conteúdo com títulos, parágrafos e imagens.</p>
</article>
</section>

<section id="contato">
<h2>Contato</h2>
<form action="#" method="post">
<p>
<label for="nome">Nome</label><br>
<input id="nome" name="nome" type="text" required>
</p>
<p>
<label for="email">E-mail</label><br>
<input id="email" name="email" type="email" required>
</p>
<p>
<label for="mensagem">Mensagem</label><br>
<textarea id="mensagem" name="mensagem" rows="4"
required></textarea>
</p>
<p>
<button type="submit">Enviar</button>
</p>
</form>
</section>

</main>
<footer>
<small>&copy; 2025 Lorena Protcz. Todos os direitos reservados.</small>
</footer>
