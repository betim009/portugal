
# 📘 Declaração de Variáveis em Portugol – Material Completo

Neste material, vamos aprender **como declarar variáveis** em Portugol, entender **para que servem**, **quais os tipos existentes** e **como usar cada uma delas com exemplos reais**.

---

## 🧠 O que é uma variável?

Uma variável é como uma **caixinha de memória** onde guardamos informações que o programa vai usar.

Essas informações podem ser:
- números inteiros (ex: 5)
- números decimais (ex: 4.5)
- textos (ex: "Olá")
- valores lógicos (ex: verdadeiro ou falso)
- letras únicas (ex: 'A')

---

## 📌 Como declarar uma variável?

No Portugol, usamos a seguinte estrutura:

```portugol
tipo nome_da_variavel
```

Exemplo:

```portugol
inteiro idade
real salario
cadeia nome
logico aprovado
caractere letra
```

---

## 🧪 Tipos de Dados em Portugol

Vamos ver cada tipo com explicações e exemplos.

---

### 🔢 1. `inteiro`

Armazena **números inteiros** (sem vírgula).

```portugol
inteiro idade
idade = 25
```

Usado para:
- Contar coisas
- Idades, quantidades, etc.

---

### 💰 2. `real`

Armazena **números com casas decimais** (quebrados).

```portugol
real altura
altura = 1.75
```

Usado para:
- Altura
- Salários
- Médias

---

### 🧾 3. `cadeia`

Armazena **textos**, ou seja, palavras e frases.

```portugol
cadeia nome
nome = "Alberto"
```

Usado para:
- Nomes
- Mensagens
- Qualquer informação com letras

---

### 🔠 4. `caractere`

Armazena **apenas um único caractere** (uma letra ou símbolo).

```portugol
caractere letra
letra = 'A'
```

Cuidado: só pode guardar **um caractere**, não uma palavra.

---

### ✅ 5. `logico`

Armazena valores **lógicos**: `verdadeiro` ou `falso`.

```portugol
logico passou
passou = verdadeiro
```

Usado em decisões, como:

```portugol
se (passou) {
    escreva("Parabéns!")
}
```

---

## 💡 Exemplo com todos os tipos juntos:

```portugol
programa {
    funcao inicio() {
        inteiro idade
        real salario
        cadeia nome
        logico aprovado

        idade = 30
        salario = 3500.50
        nome = "João Silva"
        aprovado = verdadeiro
        inicial = 'J'

        escreva("Nome: ", nome, "\n")
        escreva("Idade: ", idade, "\n")
        escreva("Salário: R$", salario, "\n")
        escreva("Aprovado? ", aprovado, "\n")
    }
}
```

---

## ⚠️ Regras para nomes de variáveis

- Não podem conter espaços
- Não podem começar com número
- Não use acentos ou caracteres especiais
- Use nomes que façam sentido (ex: `idade`, `nomeAluno`, `mediaFinal`)

---

## 📌 Dicas importantes

- Declare o tipo **antes de usar** a variável
- Cada variável deve ser **declarada apenas uma vez**
- Você pode declarar **várias variáveis do mesmo tipo** separadas por vírgula:

```portugol
inteiro a, b, c
```

- Comentários são feitos com `//` e ajudam a entender o código

---

## 🧠 Exercício proposto

1. Declare as seguintes variáveis:
   - Um número inteiro para "quantidade"
   - Um número real para "preço"
   - Um texto para "produto"
   - Um caractere para "categoria"
   - Um lógico para "emEstoque"

2. Peça ao usuário para digitar esses valores.

3. Mostre na tela o que foi digitado.

Se quiser, posso montar o gabarito depois!

---

