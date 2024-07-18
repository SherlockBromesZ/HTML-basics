## Interagindo com o Usuário: Formulários em HTML

Formulários são a porta de entrada para coletar informações dos usuários em suas páginas web. Vamos explorar os elementos chave para criá-los:

### A Tag `<form>`

A tag `<form>` define o início e o fim de um formulário em HTML.

```html
<form action="/processar_dados" method="post">
  <!-- Elementos do formulário aqui -->
</form>
```

* **action:** Especifica o endereço (URL) para onde os dados do formulário serão enviados para processamento.
* **method:** Define o método HTTP para enviar os dados (geralmente "get" ou "post").

### Entradas de Dados: `<input>`

A tag `<input>` cria diversos tipos de campos de entrada, controlados pelo atributo `type`:

| Tipo | Descrição |
|---|---|
| `text` | Caixa de texto para inserir texto livre. |
| `email` | Campo específico para endereços de email. |
| `password` | Campo que mascara a senha digitada. |
| `radio` | Botão de opção para selecionar uma única opção em um grupo. |
| `checkbox` | Caixa de seleção para marcar múltiplas opções. |
| `submit` | Botão para enviar o formulário. |

**Exemplo:**

```html
<label for="nome">Nome:</label>
<input type="text" id="nome" name="nome">

<label for="senha">Senha:</label>
<input type="password" id="senha" name="senha">
```

### Rótulos: `<label>`

A tag `<label>` fornece uma descrição para um campo de entrada. Use o atributo `for` para associá-lo ao `id` do campo correspondente.

**Exemplo:**

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email">
```

### Grupos de Opções: `radio`

Crie grupos de botões de opção (`radio`) para permitir que o usuário selecione apenas uma opção. Certifique-se de que os elementos `radio` dentro do grupo compartilhem o mesmo valor para o atributo `name`.

**Exemplo:**

```html
<p>Selecione sua faixa etária:</p>
<input type="radio" name="idade" value="0-25" id="opcao1">
<label for="opcao1">0-25</label>

<input type="radio" name="idade" value="26-50" id="opcao2">
<label for="opcao2">26-50</label>
```

### Caixas de Seleção: `<select>` e `<option>`

Use `<select>` para criar um menu suspenso com várias opções. As opções individuais são definidas com a tag `<option>`.

**Exemplo:**

```html
<label for="question">Escolha uma pergunta:</label>
<select name="question" id="question">
  <option value="q1">Qual seu nome?</option>
  <option value="q2">Qual seu animal favorito?</option>
  <option value="q3">Se você fosse uma planta, qual seria?</option>
</select>
```

### Áreas de Texto: `<textarea>`

A tag `<textarea>` cria uma área de texto para inserir várias linhas de texto.

**Exemplo:**

```html
<label for="bio">Fale sobre você:</label>
<textarea name="bio" id="bio" cols="30" rows="10" placeholder="Me fale um pouco sobre você..."></textarea>
```

### Campos Obrigatórios: `required`

Torne um campo obrigatório adicionando o atributo `required` à tag de entrada.

**Exemplo:**

```html
<label for="nome">Nome (obrigatório):</label>
<input type="text" id="nome" name="nome" required>
```

## Próximos Passos

Com este guia, você aprendeu a criar formulários interativos em HTML. Continue explorando os diferentes tipos de entrada e recursos para construir formulários eficazes para suas páginas web! 
