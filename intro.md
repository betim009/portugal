
# 📘 Introdução ao Portugol – Fundamentos Essenciais

O **Portugol** é uma linguagem fictícia usada para ensinar lógica de programação de forma simples, com comandos escritos em português. É ideal para quem está dando os primeiros passos na programação.

---

## 🧠 Conceitos Básicos

### 🔤 1. Tipos de Dados

- `inteiro`: números inteiros (ex: 1, 10, -5)
- `real`: números decimais (ex: 3.14, -2.5)
- `caractere`: um único caractere (ex: 'A', '1')
- `cadeia`: texto (ex: "Olá", "Maria")
- `logico`: verdadeiro (`verdadeiro`) ou falso (`falso`)

---

### 📥 2. Entrada de Dados

Usamos o comando `leia` para receber dados do usuário.

```portugol
cadeia nome
leia(nome)
```

---

### 📤 3. Saída de Dados

Usamos `escreva` para mostrar algo na tela.

```portugol
escreva("Olá mundo!")
```

---

### 🧮 4. Operadores

| Tipo        | Símbolo | Exemplo         |
|-------------|---------|------------------|
| Soma        | `+`     | `a + b`          |
| Subtração   | `-`     | `a - b`          |
| Multiplicação | `*`   | `a * b`          |
| Divisão     | `/`     | `a / b`          |
| Resto       | `%`     | `a % b`          |

---

### 🔁 5. Condicional (Se/Senão)

```portugol
se (idade >= 18) {
    escreva("Maior de idade")
} senao {
    escreva("Menor de idade")
}
```

---

### 🔄 6. Repetição

#### Enquanto (while)

```portugol
enquanto (x < 5) {
    escreva(x)
    x = x + 1
}
```

#### Para (for)

```portugol
para (i = 1; i <= 10; i++) {
    escreva(i)
}
```

---

### 📦 7. Função Principal

Todo programa em Portugol começa com:

```portugol
programa {
    funcao inicio() {
        // código aqui
    }
}
```

---

## 🛠️ Exemplo Completo

```portugol
programa {
    funcao inicio() {
        cadeia nome
        escreva("Digite seu nome: ")
        leia(nome)
        escreva("Olá, ", nome)
    }
}
```

---

## ✅ Dicas para Iniciantes

- Sempre comece com `programa { funcao inicio() { ... } }`
- Use `;` apenas se o seu interpretador exigir (ex: Visualg usa, Portugol Studio não)
- Teste no site: [https://portugol.dev](https://portugol.dev)
