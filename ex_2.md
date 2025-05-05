
# 🧾 Exercício de Portugol – Cardápio de Lanchonete

## 🛒 Enunciado

O cardápio de uma lanchonete é o seguinte:

| Código | Especificação     | Valor   |
|--------|--------------------|---------|
| 100    | Cachorro quente    | R$10,00 |
| 101    | Bauru simples      | R$12,00 |
| 102    | Bauru com ovo      | R$13,00 |
| 103    | Hamburguer         | R$8,00  |
| 104    | Cheeseburger       | R$9,00  |
| 105    | Refrigerante       | R$6,00  |

---

## 🧠 Tarefa

Escreva um algoritmo em **Portugol** que:
- Leia o **código** do item pedido
- Leia a **quantidade**
- Calcule e mostre o **valor a ser pago**

📌 **Importante**: a cada execução, apenas **um item** será calculado.

---

## 💻 Exemplo de Código em Portugol

```portugol
programa {
    funcao inicio() {
        inteiro codigo, quantidade
        real valor

        escreva("Digite o código do item: ")
        leia(codigo)
        
        escreva("Digite a quantidade: ")
        leia(quantidade)

        // Verifica o código e calcula o valor
        se (codigo == 100) {
            valor = 10 * quantidade
        } senao se (codigo == 101) {
            valor = 12 * quantidade
        } senao se (codigo == 102) {
            valor = 13 * quantidade
        } senao se (codigo == 103) {
            valor = 8 * quantidade
        } senao se (codigo == 104) {
            valor = 9 * quantidade
        } senao se (codigo == 105) {
            valor = 6 * quantidade
        } senao {
            escreva("Código inválido!")
            // Em portugol.dev, 'pare' pode causar erro. Use 'retorne' ou apenas finalize com escreva.
            retorne
        }

        escreva("Valor a pagar: R$", valor)
    }
}

```

---

## ✅ Dicas
- Use `inteiro` para números inteiros como código e quantidade.
- Use `real` para o valor total.
- Sempre use `senao se` para criar as opções de cardápio.
