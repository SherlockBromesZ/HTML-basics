# Tags Semânticas no HTML

As tags semânticas no HTML ajudam o navegador a entender melhor o conteúdo da sua página. Elas fornecem significado ao conteúdo que envolvem, permitindo que navegadores, mecanismos de busca e outras ferramentas identifiquem a estrutura e a hierarquia das informações.

## Principais Tags Semânticas

### `<main>`

A tag `<main>` é usada para encapsular o conteúdo principal da página. Esse conteúdo é único e diretamente relacionado ao propósito principal do documento.

Exemplo:
```html
<main>
  <h1>Bem-vindo ao Nosso Site</h1>
  <p>Este é o conteúdo principal da página.</p>
</main>
```

### `<section>`

A tag `<section>` define seções distintas de um documento, como diferentes partes de uma página, como uma seção de contato ou uma lista de avaliações.

Exemplo:
```html
<section>
  <h2>Contato</h2>
  <p>Informações de contato aqui.</p>
</section>

<section>
  <h2>Lista de Avaliações</h2>
  <ul>
    <li>Avaliação 1</li>
    <li>Avaliação 2</li>
  </ul>
</section>
```

### `<article>`

A tag `<article>` é usada para conteúdo independente que pode ser distribuído e reutilizado, como posts de blog, artigos de notícias ou qualquer outro tipo de conteúdo que faça sentido por si só.

Exemplo:
```html
<article>
  <h2>Última Notícia</h2>
  <p>Detalhes da notícia aqui.</p>
</article>
```

### `<aside>`

A tag `<aside>` é utilizada para conteúdo que está relacionado ao conteúdo principal, mas que não faz parte do fluxo principal. É frequentemente usado para barras laterais, links para conteúdos relacionados, anúncios, entre outros.

Exemplo:
```html
<aside>
  <h2>Blogs Similares</h2>
  <p>Links para blogs relacionados aqui.</p>
</aside>
```

### `<header>`

A tag `<header>` é usada para o cabeçalho de uma seção ou de um documento. Ela geralmente contém elementos como o título da seção, logotipos, ícones de navegação e outros elementos de introdução.

Exemplo:
```html
<header>
  <h1>Título do Site</h1>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#sobre">Sobre</a></li>
    </ul>
  </nav>
</header>
```

### `<footer>`

A tag `<footer>` é usada para o rodapé de uma seção ou de um documento. Normalmente contém informações como direitos autorais, links de política de privacidade, e informações de contato.

Exemplo:
```html
<footer>
  <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
</footer>
```

---

Essas tags semânticas ajudam a criar um HTML mais estruturado e compreensível, tanto para desenvolvedores quanto para navegadores e mecanismos de busca.