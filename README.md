# ESPECIFICAÇÃO DE REQUISITOS

# Projeto: Calculadora

# Atividade Ambiente Java - Etapa 01 - Requisitos
- 081190036 - Danillo Alves Rodrigues
- 081190033 - Kaio Greco Ramos

## 1. Introdução

Este documento apresenta a especificação de requisitos para a criação de uma calculadora. O objetivo é criar um código em Java utilizando o Visual Studio Code que seja capaz de operar uma calculadora com sete operações matemáticas: soma, subtração, multiplicação, divisão, radiciação, potenciação e porcentagem.

## 2. Definição de requisitos de usuário

### 2.1 Requisitos Funcionais

Informações: números de 0 a 9, operações matemáticas disponíveis, opção de limpar, campo de visualização do número, operações escolhidas pelo usuário e resposta.
Regras: O sistema deve disponibilizar ao usuário botões com símbolos que representem as operações matemáticas de soma ("+"), subtração ("-"), multiplicação ("x"), divisão ("÷"), radiciação ("√"), potenciação ("^") e porcentagem ("%"). Também deve possuir botões individuais com todos os números ("0", "1", "2", "3", "4", "5", "6", "7", "8", "9"), o símbolo ("=") com a função de finalizar as operações, o símbolo ("AC") com a função de limpar a calculadora, além de um campo de visualização das ações do usuário.
- O sistema deve validar se antes da escolha de uma operação houve a entrada de um número inicial
- O sistema deve validar se entre a escolha de uma operação e a finalização dela houve a entrada de um número.
- Caso ocorra a tentativa da divisão de algum número por 0 (zero), o campo de visualização deve apresentar uma mensagem de erro.
