## Mergulhando no HTML: Formatação e Estrutura Básicas

Este guia rápido apresenta os elementos essenciais de HTML para você começar a dar vida às suas páginas web.

### Formatação de Texto

| Tag | Descrição | Exemplo | Resultado |
|---|---|---|---|
| `<strong>` | Deixa o texto **mais forte**, ideal para destacar pontos importantes. | `<strong>Olá, Mundo!</strong>` | **Olá, Mundo!** |
| `<em>` | Coloca o texto em _itálico_, útil para ênfase sutil. | `<em>Olá, Mundo!</em>` | _Olá, Mundo!_ |
| `<small>` | Reduz o tamanho da fonte, ideal para notas e informações adicionais. | `<small>Olá, Mundo!</small>` | <small>Olá, Mundo!</small> |

### Títulos e Cabeçalhos

HTML oferece seis níveis de títulos, do maior (`<h1>`) ao menor (`<h6>`):

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Seção</h3>
```

### Listas

Crie listas ordenadas (numeradas) e não ordenadas (marcadas):

```html
<ul> <!-- Lista não ordenada -->
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

<ol> <!-- Lista ordenada -->
  <li>Primeiro item</li>
  <li>Segundo item</li>
</ol>
```

### Quebras de Linha e Regras Horizontais

* Use `<br>` para inserir uma quebra de linha simples.
* Utilize `<hr>` para criar uma linha horizontal que separa o conteúdo.

```html
<p>Este é um parágrafo.<br>Ele possui duas linhas.</p>
<hr>
<p>Este é outro parágrafo.</p>
```

### Imagens

Insira imagens com a tag `<img>`:

```html
<img src="caminho/para/imagem.jpg" alt="Descrição da imagem">
```

* **src:** Define o caminho para o arquivo da imagem.
* **alt:** Fornece uma descrição textual da imagem, importante para acessibilidade.

### Comentários

Comentários são ignorados pelo navegador e servem para você documentar seu código:

```html
<!-- Este é um comentário em HTML -->
```

## Próximos Passos

Com este guia, você aprendeu os fundamentos da formatação e estrutura em HTML. Continue explorando e construindo suas habilidades! 
