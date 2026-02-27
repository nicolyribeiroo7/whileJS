# 📘 README – Gerador de Tabuada com JavaScript

## 📌 Descrição do Projeto

Este projeto é uma página web simples que gera automaticamente a **tabuada do 1 ao 10** ao clicar em um botão.

A aplicação utiliza:

* HTML
* CSS
* JavaScript

O foco principal é praticar **estrutura de repetição (`while`)**, **laços aninhados** e **manipulação do DOM**.

---

## 🖥️ Funcionalidades

* ✅ Botão para gerar a tabuada
* ✅ Exibição das tabuadas do 1 ao 10
* ✅ Layout organizado em formato de cartões (cards)
* ✅ Uso de `while` aninhado

---

## 🏗️ Estrutura do Projeto

### 📄 HTML

A página contém:

* Um botão que chama a função `gerarTabuada()` ao ser clicado.
* Uma `<div>` com id `painel`, onde as tabuadas são exibidas dinamicamente.

---

### 🎨 CSS

O CSS é responsável pelo visual da aplicação:

* Reset básico com `*`
* Fundo escuro no `body`
* Layout em **Grid** para organizar os cards
* Estilização dos cards com:

  * Fundo branco
  * Bordas arredondadas
  * Sombra
  * Título centralizado

O Grid permite que os cards se organizem automaticamente conforme o tamanho da tela.

---

### ⚙️ JavaScript

A função principal do projeto é:

```javascript
function gerarTabuada()
```

### 🔁 Primeiro `while` (Controle da Tabuada)

Responsável por gerar as tabuadas de 1 até 10:

```javascript
while (tabuada <= 10)
```

### 🔁 Segundo `while` (Multiplicador)

Responsável por gerar as multiplicações de 1 até 10 para cada tabuada:

```javascript
while (multiplicador <= 10)
```

### 🧠 Funcionamento da Lógica

1. Uma variável `conteudo` armazena todo o HTML gerado.
2. Para cada número de 1 a 10:

   * Um card é criado.
   * São feitas as multiplicações de 1 a 10.
   * Os resultados são adicionados ao conteúdo.
3. Ao final, o conteúdo é inserido na `div` com:

```javascript
document.getElementById("painel").innerHTML = conteudo;
```


---

## 📚 Conceitos Trabalhados

* Variáveis (`let`)
* Estrutura de repetição `while`
* Laço de repetição aninhado
* Template Strings
* Manipulação do DOM
* Grid Layout
* Construção dinâmica de HTML

---


## 🎯 Objetivo Educacional

Este projeto é ideal para quem está aprendendo:

* Lógica de programação
* Estruturas de repetição
* Integração entre HTML, CSS e JavaScript
* Geração dinâmica de conteúdo na página

---


