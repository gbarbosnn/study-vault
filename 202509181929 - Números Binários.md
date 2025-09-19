Fonte: [Hardware - CS50's Understanding Technology 2017](https://www.youtube.com/watch?v=6mbFO0ZLMW8&t=29s)
### **Sistemas Numéricos: Como Computadores e Humanos Contam**

A forma como computadores e humanos processam e representam números é fundamentalmente diferente. Essa diferença reside na **base** do sistema numérico que cada um utiliza.

#### **Sistema do Computador: Binário (Base 2)**

O computador opera usando o **sistema binário**, que possui apenas dois dígitos: **0** e **1**. Cada dígito é chamado de **bit**.

- **Base:** 2
- **Dígitos:** 0 e 1 (aceita apenas esses dois valores)
- **Como funciona:** Cada posição em um número binário representa uma potência de 2 (20,21,22, etc.). Para converter um número binário para um número que entendemos, somamos as potências de 2 apenas onde o dígito binário é **1**.
#### **Sistema do Humano: Decimal (Base 10)**

Nós, humanos, usamos o **sistema decimal**, que é mais familiar. Ele utiliza dez dígitos para representar qualquer número.
- **Base:** 10
- **Dígitos:** 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- **Como funciona:** Cada posição em um número decimal representa uma potência de 10 (100,101,102, etc.). Por exemplo, o número **123** é o resultado da soma de (1×100)+(2×10)+(3×1).
---
### **Como Converter de Decimal para Binário**

Para converter um número decimal para o sistema binário, a maneira mais rápida é usar a **divisão sucessiva por 2**.

1. **Divida o número** por 2.
2. **Anote o resto** (que será sempre 0 ou 1).
3. **Continue dividindo o quociente** por 2, repetindo o processo até que o quociente seja 0.    
4. O número binário é formado pelos restos, lidos de **baixo para cima**.

**Exemplo:** Para converter **6000** para binário, você faria as divisões:

- 6000 / 2 = 3000 (resto **0**)
- 3000 / 2 = 1500 (resto **0**)
- 1500 / 2 = 750 (resto **0**)
- 750 / 2 = 375 (resto **0**)
- 375 / 2 = 187 (resto **1**)
- 187 / 2 = 93 (resto **1**)
- 93 / 2 = 46 (resto **1**)
- 46 / 2 = 23 (resto **0**)
- 23 / 2 = 11 (resto **1**)
- 11 / 2 = 5 (resto **1**) 
- 5 / 2 = 2 (resto **1**)
- 2 / 2 = 1 (resto **0**)
- 1 / 2 = 0 (resto **1**)

Lendo os restos de baixo para cima, o número binário de 6000 é **1011101110000**.