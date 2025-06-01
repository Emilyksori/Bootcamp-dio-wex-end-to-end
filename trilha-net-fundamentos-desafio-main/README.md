# 🚗 Desafio Estacionamento .NET

Este é um projeto de console desenvolvido com .NET, que simula um sistema de gerenciamento de estacionamento. O desafio faz parte da Trilha de Fundamentos .NET da DIO + WEX.

Desafio proposto no bootcamp Wex End-to-End da DIO.  
Repositório original: [link do repositório](https://github.com/digitalinnovationone/trilha-net-fundamentos-desafio)

---

## Contexto
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

---

## 🧠 Regras do Sistema

A classe `Estacionamento` deve conter os seguintes elementos:

### 🔸 Atributos

- `precoInicial` (decimal): valor fixo cobrado assim que o veículo entra.
- `precoPorHora` (decimal): valor cobrado por hora de permanência.
- `veiculos` (List\<string\>): lista com as placas dos veículos estacionados.

---

### 🔹 Métodos

- `AdicionarVeiculo()`  
  Solicita ao usuário a placa do veículo e adiciona à lista de veículos.

- `RemoverVeiculo()`  
  Solicita a placa e as horas estacionadas. Se a placa existir, calcula o valor total (preço inicial + preço por hora × horas) e exibe. Caso contrário, exibe mensagem de erro.

- `ListarVeiculos()`  
  Lista todas as placas atualmente estacionadas. Caso a lista esteja vazia, exibe:  
  `"Não há veículos estacionados."`

---


## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.

---

## 🌟 Funcionalidades

- ✅ Adicionar veículos ao estacionamento
- 🕒 Remover veículos e calcular o valor total com base no tempo estacionado
- 📋 Listar todos os veículos atualmente estacionados
- 🔍 Validação de placas (formato, duplicidade e existência)

---

## 💫 Tecnologias Utilizadas

- 💻 **.NET 9** – Plataforma para construção da aplicação de console
- 👨‍💻 **C#** – Linguagem utilizada no desenvolvimento
- 📦 **CLI .NET** – Para execução e testes via terminal

---

## 🪄 Como Executar

1. Clone ou baixe o repositório:

   ```bash
   git clone https://github.com/Emilyksori/Bootcamp-dio-wex-end-to-end.git

2. Navegue até a pasta do projeto

    ```bash
    cd trilha-net-fundamentos-desafio/DesafioFundamentos

3. Execute a aplicação

    ```bash
    dotnet run

## 📝 Exemplo de Fluxo
Informe o preço inicial e o valor por hora.

No menu principal, escolha:

- 1 para adicionar um veículo.

- 2 para remover um veículo, informando o tempo e calculando o valor total.

- 3 para listar os veículos estacionados.

- 4 para encerrar a aplicação.


## 🌸 Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de fixar os fundamentos da linguagem C# e da plataforma .NET, trabalhando com listas, estruturas condicionais, entrada e saída de dados no console e boas práticas de programação orientada a objetos.