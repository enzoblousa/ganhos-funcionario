# 💼 Ganhos do Funcionário - Mini Projeto em Java

Este projeto é uma aplicação simples em **Java** que simula o cálculo dos **ganhos mensais de um funcionário**, considerando seu salário base e os contratos realizados por hora dentro de um determinado mês.

## 🚀 Funcionalidades

- Cadastro do **departamento** e **funcionário**:
  - Nome
  - Nível de experiência (`JUNIOR`, `MID_LEVEL`, `SENIOR`)
  - Salário base

- Inclusão de múltiplos **contratos por hora**, com:
  - Data do contrato
  - Valor por hora
  - Duração em horas

- Cálculo do **ganho total em um mês específico**, considerando:
  - Salário base
  - Somatório dos contratos do mês informado

- Exibição do resultado final com:
  - Nome do funcionário
  - Departamento
  - Ganho total no mês

## 🛠️ Tecnologias utilizadas

- Java
- Programação Orientada a Objetos (POO)
- Manipulação de datas (`LocalDate`)
- Enumeração (`Enum`)
- Listas (`ArrayList`)
- Scanner para entrada de dados

## 📷 Exemplo de uso (via console)

```text
Departamento: Desenvolvimento
Nome do funcionário: João Silva
Nível: MID_LEVEL
Salário base: 3000.00
Quantos contratos para este funcionário? 2

Digite os dados do contrato #1:
Data (DD/MM/AAAA): 15/03/2025
Valor por hora: 50.00
Duração (horas): 10

Digite os dados do contrato #2:
Data (DD/MM/AAAA): 20/03/2025
Valor por hora: 60.00
Duração (horas): 5

Digite o mês e ano para calcular os ganhos (MM/AAAA): 03/2025

Nome: João Silva
Departamento: Desenvolvimento
Ganhos em 03/2025: 3800.00
