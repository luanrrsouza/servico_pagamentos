Serviço de Pagamentos - Interface e POO

Este é um projeto simples desenvolvido para treinar conceitos de interface e programação orientada a objetos (POO) em Java.

Tecnologias Utilizadas

Java

Conceitos de Interface e POO

Scanner para entrada de dados

DateTimeFormatter para manipulação de datas

Estrutura do Projeto

O projeto está organizado da seguinte forma:

/src
 |-- application
 |   |-- Main.java   # Classe principal
 |
 |-- entities
 |   |-- Contract.java   # Classe que representa um contrato
 |   |-- Installment.java   # Classe que representa uma parcela do contrato
 |
 |-- services
 |   |-- ContractService.java   # Classe que processa o contrato
 |   |-- OnlinePaymentService.java   # Interface para serviço de pagamento online
 |   |-- PaypalService.java   # Implementação da interface para pagamentos via PayPal

Como Funciona

O sistema solicita ao usuário os seguintes dados:

Número do contrato

Data do contrato (no formato dd/MM/yyyy)

Valor total do contrato

Quantidade de parcelas

Com essas informações, o sistema processa os pagamentos e exibe as parcelas geradas.

Como Executar

Clone o repositório:

git clone https://github.com/luanrrsouza/servico_pagamentos.git

Abra o projeto em sua IDE preferida (IntelliJ, Eclipse, VS Code, etc.)

Compile e execute a classe Main.java

Melhorias Futuras

Implementação de novos serviços de pagamento além do PayPal

Interface gráfica para facilitar o uso

Testes unitários para garantir a robustez do sistema
