# Funções em JavaScript

## O que são Funções?

Funções em programação são blocos reutilizáveis de código que realizam uma tarefa específica ou calculam um valor. Elas ajudam a organizar e estruturar o código, permitindo a modularidade e a reutilização.

## Declaração de Funções em JavaScript:

#### Sintaxe Básica: 

![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/214a97b7-0228-47a6-9584-6f7f905a76a2)

#### Parâmetros 

**Parâmetros:**
  São variáveis utilizadas pela função para receber valores durante a chamada.
  Parâmetros são valores que podem ser passados para uma função quando ela é chamada. Esses valores fornecidos à função são usados dentro do corpo da função para realizar operações ou cálculos. Em JavaScript, os parâmetros são definidos entre os parênteses durante a declaração da função.

  ![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/9baba4ff-d78d-4299-8f7d-05a504d0000f)

  Neste exemplo, a função somarDoisNumeros tem dois parâmetros (a e b). Quando a função é chamada com somarDoisNumeros(3, 5), os valores 3 e 5 são passados como argumentos para os parâmetros a e b, respectivamente. Dentro do corpo da função, esses valores são somados e o resultado é retornado.

  **Parâmetros com Valores Padrão:**

  Você também pode atribuir valores padrão aos parâmetros, que serão utilizados caso nenhum valor seja fornecido durante a chamada da função.

  ![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/583a5948-94df-4409-926c-7708733b6e53)

  Neste exemplo, se nenhum argumento for passado para o parâmetro nome, o valor padrão "Visitante" será utilizado.

###  Argumentos e Parâmetros:

**Parâmetros:**  São as variáveis listadas na declaração da função.
**Argumentos:** São os valores reais passados para a função durante a chamada.

![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/a6ca68f4-0723-4576-8c65-bcc8b8977a17)

### Conclusão:
Parâmetros são essenciais para tornar as funções mais flexíveis e reutilizáveis. Eles permitem que você adapte o comportamento da função com base nos valores fornecidos durante sua chamada.


## Return 
O **return** em JavaScript é uma palavra-chave usada para especificar o valor que uma função deve retornar. Quando uma função é chamada, ela pode realizar operações e, opcionalmente, retornar um resultado para o código que fez a chamada.

**Exemplo de Função com Retorno:**
![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/cbeafc79-f66f-4734-aa82-8ac138fed6af)

Neste exemplo, a função** multiplicar** aceita dois **parâmetros (a e b)** e retorna o resultado da **multiplicação**. A chamada da função **multiplicar(5, 8)** retorna **40**, que é então atribuído à variável **resultadoMultiplicacao** e exibido no console.

### Funções sem Retorno:
Funções em JavaScript não são obrigadas a ter um comando **return**. Se uma função não contiver um **return** ou se o **return** não especificar um valor, a função retornará **undefined**.

![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/b4de8e67-73fa-413d-b025-589f469aa72a)


### Utilização de return para Finalizar uma Função:

![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/54309e9d-604f-457b-9872-446f783c1188)


## Escopo de Variáveis:

O escopo em programação refere-se à visibilidade e acessibilidade de variáveis em diferentes partes do código. Em JavaScript, há o escopo global e o escopo local.


## Escopo Global e Local:

### Escopo Global:
Variáveis declaradas fora de qualquer função têm escopo global. Elas podem ser acessadas de qualquer parte do código.
Isso significa que elas podem ser acessadas de qualquer lugar do código, tanto dentro quanto fora de funções.

Exemplo:
![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/ca8b58fc-2820-4138-8272-a3e151bbb41d)

Variáveis globais são acessíveis em todo o código, mas também podem ser modificadas de qualquer lugar, o que pode levar a efeitos colaterais indesejados.

## Escopo Local: 
Variáveis declaradas dentro de uma função têm escopo local. Elas são visíveis apenas dentro dessa função.  Isso significa que elas só podem ser acessadas dentro dessa função.

#### Exemplo: 
![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/2306717f-8568-4ac3-9ac3-38a98a7aad9f)

#### Exemplo:

![image](https://github.com/Midssouza/Logica_de_Programacao/assets/60756132/714c8d0d-2a40-4d34-8aef-37273301acb9)

Variáveis locais são úteis para armazenar dados temporários e evitar interferências externas no restante do código.


## Conclusão:

Funções são uma parte fundamental da programação em JavaScript. Elas oferecem uma maneira de estruturar o código, promovem a reutilização e modularidade, e facilitam a manutenção do código.

Entender como declarar funções, utilizar parâmetros e retorno, e compreender o escopo de variáveis é essencial para se tornar um desenvolvedor eficaz em JavaScript.

Entender o escopo global e local é fundamental para evitar conflitos de variáveis e criar código mais modular e fácil de manter. Ao limitar a visibilidade das variáveis ao escopo necessário, você reduz a chance de erros e torna seu código mais robusto.
