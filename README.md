# Calculadora de Descontos

## Descrição do Projeto

Este projeto consiste em uma aplicação web destinada ao cálculo de descontos em produtos. O usuário pode selecionar uma categoria, inserir o valor do produto e consultar automaticamente o valor descontado, o total final após o desconto e a porcentagem aplicada. O objetivo é oferecer uma interface simples, direta e funcional, simulando um sistema básico de cálculo utilizado em lojas.

## Funcionalidades

- Menu interativo para seleção de categorias.
- Campo para inserção do valor do produto.
- Cálculo automático do valor final, valor do desconto e percentual aplicado.
- Interface responsiva desenvolvida com HTML e CSS.
- Atualização dinâmica dos resultados por meio de JavaScript.


## Como Executar

1. Faça o download ou clone o repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Selecione a categoria desejada no menu.
4. Insira o valor do produto.
5. Clique no botão de cálculo para visualizar os resultados na tela.

## Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript  
- Font Awesome (ícones)  
- Uiverse.io (modelos de componentes utilizados como referência)

## Lógica Básica de Cálculo

```javascript
let preco = 100;
let desconto = 0.10;

let valorDescontado = preco * desconto;
let totalFinal = preco - valorDescontado;


