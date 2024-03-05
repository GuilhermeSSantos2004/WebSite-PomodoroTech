# Projeto de Aprendizado: Manipulação do DOM com JavaScript

Neste projeto, você terá a oportunidade de aprimorar suas habilidades em manipulação do DOM (Document Object Model) usando JavaScript. Ao longo do projeto, você aprenderá a utilizar várias técnicas e métodos essenciais para dinamicamente alterar o conteúdo e a aparência de uma página web.

## Aprendizados Principais

### 1. InnerHTML para Alteração de Textos

Utilizamos o método `innerHTML` para dinamicamente alterar o conteúdo de elementos HTML, proporcionando uma experiência interativa ao usuário.

```javascript
// Exemplo de uso do innerHTML para alterar o texto da tag <h1>
const meuElemento = document.getElementById("meuElemento");
meuElemento.innerHTML = "Novo Texto Dinâmico";
```

### 2. setAttribute para Alteração de Caminhos de Imagens

Aprenda a modificar dinamicamente os caminhos de imagens em sua página usando o método `setAttribute`.

```javascript
// Exemplo de uso do setAttribute para alterar o caminho da imagem
const minhaImagem = document.getElementById("minhaImagem");
minhaImagem.setAttribute("src", "caminho/nova-imagem.jpg");
```

### 3. classList para Alteração de Classes e Estilo

Explore o uso da `classList` para adicionar, remover e alternar classes em elementos, possibilitando alterações no estilo da página de maneira dinâmica.

```javascript
// Exemplo de uso da classList para adicionar uma classe
const meuBotao = document.getElementById("meuBotao");
meuBotao.classList.add("nova-classe");
```

### 4. querySelector para Seleção de Elementos

Entenda como utilizar o `querySelector` para selecionar elementos de forma flexível, utilizando seletores CSS.

```javascript
// Exemplo de uso do querySelector para selecionar um elemento por classe
const elementoSelecionado = document.querySelector(".minha-classe");
```

### 5. addEventListener para Escutar Interações

Aprenda a usar `addEventListener` para detectar e responder a eventos, como cliques de botões, proporcionando uma interação dinâmica com o usuário.

```javascript
// Exemplo de uso do addEventListener para escutar o clique em um botão
const meuBotao = document.getElementById("meuBotao");
meuBotao.addEventListener("click", function() {
  alert("Botão clicado!");
});
```

Explore esses conceitos neste projeto prático e fortaleça suas habilidades na manipulação do DOM com JavaScript. Ao final, você terá uma compreensão sólida desses métodos essenciais para criar páginas web interativas e dinâmicas.
