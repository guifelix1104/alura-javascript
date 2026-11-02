# Desafios de JavaScript - Alura

Exercícios de lógica de programação em JavaScript feitos no VS Code durante o curso da Alura.

---

## Desafio 1
Mostre um alerta com a mensagem "Boas vindas ao nosso site!".

```javascript
alert('Boas vindas ao nosso site');
```

---

## Desafio 2
Declare uma variável chamada `nome` e atribua a ela o valor "Lua".

```javascript
let nome = "Lua";
```

---

## Desafio 3
Crie uma variável chamada `idade` e atribua a ela o valor 25.

```javascript
let idade = 25;
```

---

## Desafio 4
Defina uma variável `numeroDeVendas` e atribua a ela o valor 50.

```javascript
let numeroDeVendas = 50;
```

---

## Desafio 5
Defina uma variável `saldoDisponivel` e atribua a ela o valor 1000.

```javascript
let saldoDisponivel = 1000;
```

---

## Desafio 6
Exiba um alerta com o texto "Erro! Preencha todos os campos".

```javascript
alert('Erro! Preencha todos os campos');
```

---

## Desafio 7
Declare uma variável chamada `mensagemDeErro` e atribua a ela o valor "Erro! Preencha todos os campos". Agora exiba um alerta com o valor da variável `mensagemDeErro`.

```javascript
let mensagemDeErro = "Erro! Preencha todos os campos";
alert(mensagemDeErro);
```

---

## Desafio 8
Use um novo prompt para perguntar o nome do usuário e armazená-lo em uma variável.

```javascript
let nome = prompt('Digite o seu nome');
```

> Obs.: errei este exercício na primeira tentativa (usei `let qualSeuNome = prompt("Qual é o seu nome?")`).

---

## Desafio 9
Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável `idade`.

```javascript
let idade = prompt('Digite a sua idade');
```

> Obs.: não soube resolver sozinha, então consultei a resposta para aprender.

---

## Desafio 10
Para validar a idade capturada no desafio 9: caso a idade seja maior ou igual a 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".

```javascript
let idade = prompt('Digite a sua idade');
if (idade >= 18) {
    alert('Voce pode tirar a habilitação!');
} else {
    alert('Voce não pode tirar a habilitação!');
}
```

> Obs.: o `else` não era pedido, adicionei só para testar.
