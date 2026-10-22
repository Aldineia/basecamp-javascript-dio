
# Variáveis e Tipos - Javascript (DIO)

# Comparador de Números - Desafio DIO

Neste repositório, você encontrará a minha resolução para as atividades práticas propostas no curso de **"Variáveis e Tipos"** do basecamp de JavaScript.

O objetvo deste módulo foi consolidar o entendimento sobre a manipulação de string, array, operadores lógicos e estruturas de repetição em JavaScript, além de praticar a execução de scripts diretamente pelo terminal **Bash**.

---

## Tecnologias Utilizadas

* **JavaScript (ES6+)**
* **Node.js** (para execução local dos scripts)
* **Git & Bash** (para controle de versão e navegação no terminal)
* **Visual Studio Code** (Editor de código)

---

## Atividades Práticas Desenvolvidas

### Atividade 1: Verificador de Palíndromo

O desafio consistia em validar se uma determinada string era um palíndromo (frase ou palavra que se lê igual de frente para trás e de trás para frente). Foram implementadas duas abordagens diferentes:

* **Solução 1 (Manipulação de Métodos):** Utiliza os métodos nativos `.split()`, `reverse()`, e `.join()`para inverter a string e compará-la com o valor original.

* **Solução 2 (Abordagem com For Loop / Two Pointers):** Uma solução mais performática que percorre apenas até a metade da string (´`length / 2`), comparando os caracteres das estremidades opostas passo a passo.

## Ativodade 2: Substituidor de Números Pares

Uma função que recebe a array de número e substitui todos os elemnetos  que sejam pares e diferentes de zero pelo nímero `0`. 
* Caso o array recebido seja vazio ou enexistente, a função retorna `-1`.
