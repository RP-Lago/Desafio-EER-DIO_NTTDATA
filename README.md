Projeto de Modelagem de Dados com Diagrama EER

Este projeto foi desenvolvido como parte de um desafio do bootcamp oferecido pela **[Digital Innovation One - DIO](https://www.dio.me/)** em parceria com a **[NTT DATA](https://www.nttdata.com/)**. O objetivo deste desafio foi a criação de um esquema de modelagem de dados utilizando o **Diagrama EER (Entity-Relationship Enhanced)** para representar um sistema acadêmico focado em professores, disciplinas e departamentos, seguindo o conceito de **Star Schema**.

## Estrutura do Projeto

O projeto contém um esquema de banco de dados relacional que inclui as seguintes tabelas:

- **Professor**: Tabela que armazena os dados dos professores, como nome, titulação e área de expertise.
- **Departamento**: Informações sobre os departamentos e seus respectivos campi.
- **Disciplina**: Tabela para armazenar as disciplinas oferecidas.
- **Curso**: Informações sobre os cursos disponíveis.
- **Fato_Professor**: Tabela de fatos que relaciona professores com departamentos, cursos e disciplinas, além de registrar as horas ministradas.
- **Data**: Tabela de tempo que inclui dados de ano, mês, dia e dia da semana, usada para análise temporal.

## Diagrama EER

Abaixo está o diagrama **EER (Entity-Relationship Enhanced)**, que foi criado para representar as relações entre as tabelas deste projeto.
![image](https://github.com/user-attachments/assets/c6178cde-796c-4cd3-b71d-58645b98109a)


## Modelo de Relacionamento

O modelo adotado segue uma estrutura em **Star Schema**, com a tabela de fatos `Fato_Professor` no centro, conectada às tabelas dimensionais que armazenam as descrições e atributos relevantes para a análise de dados.

