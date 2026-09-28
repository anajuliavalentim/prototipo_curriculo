# prototipo_curriculo
# 💼📋 Portfólio / Currículo Web

Projeto desenvolvido como parte de um desafio prático de **HTML5**, com o objetivo de criar uma página de **Portfólio / Currículo Web** utilizando uma estrutura organizada, semântica e funcional.

## 🎯 Objetivo

Desenvolver uma página HTML que apresente informações profissionais de um desenvolvedor, incluindo:

* 👤 Informações pessoais
* 📝 Apresentação profissional
* 💻 Habilidades
* 📂 Projetos
* 📋 Tabela de projetos
* 📧 Formulário de contato
* 📞 Informações de contato

O projeto busca demonstrar o conhecimento na utilização de **HTML5 semântico**, seguindo a organização apresentada no modelo do desafio.

## 🛠️ Tecnologias Utilizadas

* 🌐 **HTML5**
* 📝 HTML Semântico
* 🔗 Links e âncoras
* 📊 Tabelas
* 📋 Formulários

## 📌 Estrutura do Projeto

### 👤 Sobre Mim

A seção apresenta:

* Foto de perfil com tamanho **150x150 pixels**;
* Texto de apresentação;
* Lista de habilidades profissionais.

### 💻 Meus Projetos

Os projetos são organizados em uma tabela contendo:

| Projeto   | Tecnologias | Status       | Link    |
| --------- | ----------- | ------------ | ------- |
| Projeto 1 | HTML5       | Concluído    | Acessar |
| Projeto 2 | HTML5       | Em andamento | Acessar |
| Projeto 3 | HTML5       | Concluído    | Acessar |

A tabela utiliza corretamente as tags:

* `<table>`
* `<thead>`
* `<tbody>`
* `<tr>`
* `<th>`
* `<td>`

### 📧 Entre em Contato

O formulário é organizado dentro de um `<fieldset>` com o título **"Dados do Contato"**.

Ele contém:

* 👤 Campo para Nome;
* 📧 Campo para E-mail;
* 📋 Menu de seleção para Assunto;
* 💬 Área de texto para Mensagem;
* 📤 Botão de envio.

Todos os campos possuem seus respectivos `<label>` vinculados corretamente.

## 🧱 Estrutura HTML

O projeto utiliza elementos semânticos do HTML5, como:

```html
<header>
<nav>
<main>
<section>
<table>
<fieldset>
<footer>
```

Essa estrutura ajuda a organizar o conteúdo e facilita a compreensão da página.

## 🔗 Navegação

O menu possui links internos utilizando **âncoras HTML**, permitindo navegar diretamente entre as seções da página:

```html
<a href="#sobre">Sobre</a>
<a href="#projetos">Projetos</a>
<a href="#contato">Contato</a>
```

## 🖼️ Foto de Perfil

A imagem de perfil foi configurada com as dimensões exigidas:

```html
<img src="foto.jpg" width="150" height="150" alt="Foto de perfil">
```

## 📋 Formulário

O formulário utiliza `<fieldset>` e `<legend>` para agrupar os dados:

```html
<fieldset>
    <legend>Dados do Contato</legend>
    
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">

    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email">

    <label for="assunto">Assunto:</label>
    <select id="assunto" name="assunto">
        <option>Contato</option>
        <option>Projeto</option>
    </select>

    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" name="mensagem"></textarea>

    <button type="submit">Enviar</button>
</fieldset>
```

## 📞 Rodapé

O rodapé apresenta as informações de contato e utiliza o caractere especial `&copy;` para representar o símbolo de direitos autorais.

Exemplo:

```html
<footer>
    &copy; 2026 - Portfólio Web
    <br>
    E-mail: contato@email.com
    <br>
    Telefone: (11) 99999-9999
</footer>
```

## 🏆 O que foi praticado

Com este desafio, foram praticados conceitos importantes de desenvolvimento Web:

* ✅ Estrutura básica do HTML5
* ✅ Tags semânticas
* ✅ Navegação por âncoras
* ✅ Criação e organização de tabelas
* ✅ Criação de formulários
* ✅ Uso de `<fieldset>` e `<legend>`
* ✅ Associação entre `<label>` e campos
* ✅ Inserção e dimensionamento de imagens
* ✅ Links e hiperlinks
* ✅ Caracteres especiais do HTML

## 🚀 Resultado

O projeto apresenta um **Portfólio / Currículo Web completo**, organizado e funcional, colocando em prática os principais recursos de estruturação do **HTML5**.

---

📚 **Projeto desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento Web.**
