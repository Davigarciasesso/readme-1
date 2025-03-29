# Projeto Banco

## Descrição
O projeto **Banco** é uma aplicação simples de simulação de uma conta corrente. Ele permite ao usuário criar uma conta, consultar saldo, realizar depósitos e saques com a restrição de que o saque não pode ultrapassar 20% do saldo disponível.

## Funcionalidades
- Criar uma conta corrente com nome do titular e saldo inicial
- Consultar saldo da conta
- Realizar depósitos
- Realizar saques respeitando a regra de 20% do saldo

## Tecnologias Utilizadas
- Java
- Scanner (para entrada de dados do usuário)

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Compile o código Java:
   ```bash
   javac Main.java
   ```
3. Execute o programa:
   ```bash
   java Main
   ```

## Exemplo de Uso
```bash
Digite o nome do titular da conta: João Silva
Digite o saldo inicial: 1000
Saldo atual: R$1000.00
Digite o valor a depositar: 500
Depósito realizado com sucesso!
Saldo após depósito: R$1500.00
Digite o valor a sacar: 400
Saque negado! O valor deve ser no máximo 20% do saldo atual.
```

## Autor
[Seu Nome]

## Licença
Este projeto é de uso educacional e pode ser modificado livremente.
