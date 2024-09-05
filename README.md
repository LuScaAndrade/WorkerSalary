# Worker Income Calculator

Este projeto é um exemplo de aplicação em Java que calcula a renda de um trabalhador em um determinado mês, levando em conta os contratos por hora que ele firmou.

## Funcionalidades

- **Cadastro de trabalhador:** Nome, nível de experiência (JUNIOR, MID_LEVEL, SENIOR) e salário base.
- **Associação a um departamento:** O trabalhador é associado a um departamento específico.
- **Registro de contratos:** Permite registrar múltiplos contratos de trabalho por hora, incluindo data, valor por hora e duração.
- **Cálculo de renda:** Calcula a renda do trabalhador para um mês específico, somando o salário base e o valor total dos contratos realizados naquele mês.

## Estrutura do Projeto

O projeto está dividido em vários pacotes e classes:

- **entities:** Contém as classes principais que representam o trabalhador, departamento e contrato de trabalho.
  - `Worker`: Representa o trabalhador.
  - `Department`: Representa o departamento do trabalhador.
  - `HourContract`: Representa um contrato de trabalho por hora.
- **enums:** Contém a enumeração `WorkerLevel`, que define os níveis de experiência do trabalhador (`JUNIOR`, `MID_LEVEL`, `SENIOR`).
- **application:** Contém a classe `Program`, que é o ponto de entrada do programa.

## Como Usar

1. **Executar o programa:** Ao iniciar o programa, você será solicitado a inserir o nome do departamento e os dados do trabalhador.
2. **Registrar contratos:** Você poderá registrar contratos de trabalho para o trabalhador, especificando a data, o valor por hora e a duração em horas.
3. **Calcular a renda:** Informe o mês e o ano para o qual deseja calcular a renda. O programa exibirá a renda total do trabalhador naquele período, somando o salário base e os contratos realizados no mês.

## Exemplo de Uso
Enter Department name's: Sales Enter Worker data: Name: John Doe Level: MID_LEVEL Base Salary: 3000.00

How many contracts to this worker? 2

Enter contract #1 data: Date (DD/MM/YYYY): 15/08/2024 Value per Hour: 50.00 Duration (Hours): 20

Enter contract #2 data: Date (DD/MM/YYYY): 25/08/2024 Value per Hour: 80.00 Duration (Hours): 10

Enter the month and year to calculate income (MM/YYYY): 08/2024

Name: John Doe Department: Sales Income for 08/2024: 4000.00

## Tecnologias Utilizadas

- **Java:** Linguagem de programação principal.
- **Java.util.Calendar:** Para manipulação de datas.
- **Java.util.Scanner:** Para entrada de dados do usuário.
- **SimpleDateFormat:** Para formatação de datas.

## Como Executar

1. Clone este repositório.
2. Compile e execute a classe `Program` para iniciar o programa.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.


