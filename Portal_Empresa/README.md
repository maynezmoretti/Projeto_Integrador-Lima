# PROJETO INTEGRADOR FINAL – MÓDULO HTML5

## Portal Institucional – GlobalWear

Projeto desenvolvido para a Unidade Curricular **LIMA – Linguagem de Marcação**, do curso Técnico em Desenvolvimento de Sistemas.

O projeto consiste no desenvolvimento de um **portal institucional completo utilizando HTML5**, aplicando conceitos de estrutura, semântica, navegação, formulários, tabelas, imagens, acessibilidade e organização de conteúdo.

Além das páginas institucionais, também foi desenvolvido um **catálogo de produtos**, permitindo apresentar as camisetas de seleções disponíveis na GlobalWear.

---

## Sobre o Projeto

A **GlobalWear** é uma empresa fictícia voltada para a venda de camisetas de seleções de futebol da Copa do Mundo.

O site foi desenvolvido com o objetivo de apresentar a empresa, seus serviços, produtos e formas de contato, utilizando uma estrutura organizada e acessível.

O projeto foi criado exclusivamente para fins educacionais.

---

## Objetivos

O projeto tem como principais objetivos:

* Desenvolver páginas utilizando HTML5.
* Aplicar elementos semânticos.
* Criar navegação entre diferentes páginas.
* Organizar informações de forma estruturada.
* Criar um catálogo de produtos.
* Utilizar imagens com textos alternativos.
* Criar tabelas para apresentação de informações.
* Desenvolver um formulário de contato.
* Aplicar recursos básicos de acessibilidade.
* Organizar corretamente os arquivos do projeto.

---

## Tecnologias Utilizadas

* HTML5
* Git
* GitHub

---

## Estrutura do Projeto

```text
portal-empresa/
│
├── index.html
├── sobre.html
├── servicos.html
├── catalogo.html
├── contato.html
│
└── imagens/
    ├── logo.png
    ├── brasil.jpg
    ├── franca.jpg
    ├── argentina.jpg
    └── ...
```

---

## Páginas do Site

### Página Inicial

Arquivo:

```text
index.html
```

Apresenta:

* Nome da empresa;
* Logotipo;
* Apresentação da GlobalWear;
* Menu de navegação;
* Destaques da empresa;
* Acesso ao catálogo.

### Sobre Nós

Arquivo:

```text
sobre.html
```

Apresenta informações sobre:

* História da empresa;
* Missão;
* Visão;
* Valores;
* Imagem institucional.

### Serviços

Arquivo:

```text
servicos.html
```

Apresenta:

* Serviços oferecidos;
* Descrição dos serviços;
* Tabela de informações;
* Categorias e preços.

### Catálogo

Arquivo:

```text
catalogo.html
```

O catálogo foi desenvolvido para apresentar os produtos da GlobalWear de maneira organizada.

Nele são apresentadas diferentes **camisetas de seleções de futebol**, contendo informações como:

* Nome da seleção;
* Imagem da camiseta;
* Descrição do produto;
* Categoria;
* Preço.

O catálogo permite que o visitante conheça os produtos oferecidos pela empresa antes de entrar em contato.

### Contato

Arquivo:

```text
contato.html
```

Apresenta:

* Nome;
* E-mail;
* Telefone;
* Assunto;
* Mensagem;
* Dados de contato;
* Horário de atendimento;
* Formulário com validações HTML5.

---

## Catálogo de Produtos

Uma das partes desenvolvidas no projeto foi o **catálogo de camisetas da GlobalWear**.

O catálogo utiliza imagens e informações dos produtos para organizar as opções disponíveis para os clientes.

Exemplo de organização:

| Produto                | Seleção    | Categoria |
| ---------------------- | ---------- | --------- |
| Camiseta do Brasil     | Brasil     | Seleções  |
| Camiseta da França     | França     | Seleções  |
| Camiseta da Argentina  | Argentina  | Seleções  |
| Camiseta de Cabo Verde | Cabo Verde | Seleções  |

---

## Recursos HTML5 Utilizados

Durante o desenvolvimento foram utilizados diversos recursos estudados no módulo, incluindo:

### Estrutura semântica

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

### Títulos

```html
<h1>
<h2>
<h3>
```

### Textos

```html
<p>
```

### Listas

```html
<ul>
<ol>
<li>
```

### Imagens

As imagens possuem o atributo `alt` para melhorar a acessibilidade:

```html
<img src="imagens/logo.png" alt="Logo da GlobalWear">
```

### Links

A navegação entre as páginas é realizada utilizando links HTML:

```html
<a href="catalogo.html">Catálogo</a>
```

---

## Tabela

A página de serviços possui uma tabela para organizar informações sobre os serviços oferecidos.

Exemplo:

| Serviço                | Categoria      | Preço     |
| ---------------------- | -------------- | --------- |
| Camisas de Seleções    | Vestuário      | R$ 129,90 |
| Camisas Personalizadas | Personalização | R$ 149,90 |
| Camisas Esportivas     | Vestuário      | R$ 119,90 |

---

## Formulário de Contato

A página de contato possui um formulário utilizando recursos de HTML5.

São utilizados:

* `label`
* `input`
* `select`
* `textarea`
* `placeholder`
* `required`
* botão de envio

Exemplo:

```html
<label for="nome">Nome:</label>
<input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>
```

---

## Acessibilidade

O projeto aplica recursos básicos de acessibilidade, como:

* Definição do idioma da página com `lang="pt-BR"`;
* Utilização de `meta charset="UTF-8"`;
* Hierarquia correta de títulos;
* Utilização de `label` nos campos do formulário;
* Texto alternativo nas imagens utilizando `alt`;
* Utilização de elementos semânticos do HTML5.

---

## Navegação

O portal possui navegação entre as páginas institucionais, catálogo e contato.

```text
Página Inicial
      │
      ├── Sobre Nós
      │
      ├── Serviços
      │
      ├── Catálogo
      │
      └── Contato
```

---

## Autores

**Julia Guerra Menoni, Mayne Zardo Moretti e Murilo Santos da Silva**

Curso: **Técnico em Desenvolvimento de Sistemas**

Unidade Curricular: **LIMA – Linguagem de Marcação**

Projeto desenvolvido para fins educacionais.