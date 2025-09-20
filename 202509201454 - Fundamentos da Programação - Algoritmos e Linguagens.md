#programação #fundamentos

Fonte: [CS50x 2025 - Lecture 2 - Arrays](https://www.youtube.com/watch?v=Y8qnryVy5sQ&list=PLhQjrBD2T383q7Vn8QnTsVgSvyLpsqL_R&index=4)

MOC Relacionado: [[Fundamentos_MOC]]

Programar um computador é, essencialmente, dar a ele um conjunto de instruções para executar uma tarefa. Essas instruções são escritas usando **algoritmos**.
#### **O que é um Algoritmo?**

Um **algoritmo** é uma sequência de passos lógicos e bem definidos que tem um início e um fim. Ele serve como a "receita" para resolver um problema. Um algoritmo não precisa ser complexo; pode ser algo simples, como os passos para fritar um ovo.
#### **Linguagens de Programação**

Para traduzir os algoritmos em instruções que o computador entende, usamos **linguagens de programação**. Essas linguagens podem ser divididas em dois grupos principais:

- **Linguagens Compiladas:** Como **C** ou **Java**, elas precisam de um processo chamado **compilação** antes de serem executadas.

- **Linguagens Interpretadas:** Como **Python** ou **JavaScript**, elas são executadas linha por linha por um "intérprete", sem a necessidade de um processo de compilação prévio.

### **O Processo de Compilação**

A compilação é o processo de traduzir o código-fonte que você escreveu (em uma linguagem como C) para o código de máquina (binário), que é o idioma nativo do computador. Esse processo é dividido em quatro etapas:

1. **Pré-processamento:** O pré-processador busca e inclui o código de outras bibliotecas ou arquivos referenciados no seu código principal. Pense nisso como "copiar e colar" todo o código necessário em um único arquivo.

2. **Compilação Real:** O compilador traduz o código pré-processado para uma linguagem intermediária de baixo nível, chamada **Assembly**. Esta é uma linguagem mais próxima do hardware, mas ainda legível para programadores.

3. **Montagem (Assembly):** O montador converte o código Assembly para a linguagem binária (sequências de 0s e 1s). O computador agora consegue entender essas instruções.

4. **Vinculação (Linking):** O vinculador (ou _linker_) une todos os blocos de código binário gerados — tanto do seu arquivo original quanto das bibliotecas incluídas — em um único e coeso arquivo executável. É esse arquivo final que você executa.