# Projeto Integrador (PI) - 2º ADS - A

 

## Disciplinas

 - __Sistemas de Informação:__ profº Walmir
 - __Engenharia de Software I:__ profº Giuliano Bertoti 
 - __Linguagem de Programação:__ profª Juliana

 

## Equipe

 - __Product Owner:__ Guilherme Oliveira Pontes Alvarenga - RA
 - __Scrum Master:__ Diego Rodrigo da Silva - RA
 - João Vitor de Oliveira Soeiro - RA
 - Rodrigo Félix da Silva - RA
 - Thalles Santos Torres - RA
 - William Daisuke Honda - RA
 
# Cronograma

![](https://i.imgur.com/PBrsF9g.jpg)

# Sprints

## Lista de Histórias de Usuário
![](https://i.imgur.com/Ls0pD0e.jpg)

## Histórico das Sprints

**Sprint 2 ([LINK DA PASTA](https://github.com/ThallesTorres/Projeto_SPC/tree/master/SPRINT%202)):**
 - Finalização das Histórias de Usuário
 - Desenho dos Diagramas de Casos de Uso
 - Esboço da lógica de programação em documento jupyter notebook
 - Tratamento dos dados:
     - Contar linhas com valores únicos
     - Verificar recência dos dados
     - Contar linhas com campos completos e desprezar os invalidados nas análises
     - Validar as modalidades
     - Verificar recência dos dados
     - Contar número de clientes únicos por modalidade
     - Contar número de movimentações por modalidade
     - Valor total das faturas no cartão de crédito
     - Valor mínimo das faturas no cartão de crédito
     - Número de operações por modalidade
     - Valor contratado e saldo devedor por modalidade
     - Número de parcelas por modalidade
     - Número de pagamentos por modalidade
     - Número de registros vencidos por modalidade
 
**Sprint 1 ([LINK DA PASTA](https://github.com/ThallesTorres/Projeto_SPC/tree/master/SPRINT%201)):**
 - Levantamento de Requisitos
 - Esboço da lógica de programação em documento jupyter notebook
 - Análise e tratamento dos dados:
     - Contar CNPJs válidas
     - Valor das parcelas totais por modalidade
     - Quantidade de operações mais utilizadas por modalidade
 - Início do levantamento das histórias de Usuário


# Requisitos

## Levantamento dos Requisitos
 - Da primeira apresentação da equipe do SPC, dia 10/02/2020, que explicou o que é a empresa, seu funcionamento e dimensão de negócios, e por fim o desafio desse projeto, onde são apresentados os objetivos, os indicadores de qualidade e de negócio desejados.
 - Segunda reunião, dia 05/03/2020, na qual foram feitas entrevistas sobre os dados disponibilidades, necessidades do cliente e restrições de projeto.
 - Discussões internas do time realizadas entre os dias 10/02/2020 e 16/03/2020, sobre os objetivos propostos e as possibilidades de trabalho, com consequente documentação e desenho do diagrama de casos de uso.

## Objetivo

**Objetivo Geral:**

 - Adequar-se ao Cadastro Positivo:
     - Garantindo qualidade dos dados;
     - Uso adequado;
     - Gerar valor através dos dados.

**Espeficicações do Objetivo:**
 - Atender a legislação do Cadastro Positivo;
 - Analisar a qualidade dos dados recebidos;
 - Analisar as movimentações do Cadastro Positivo;
 - Analisar o perfil dos consumidores;
 - Identificar tendências dos consumidores.

**Requisições do cliente:**
 - Apresentar graficamente a qualidade dos dados (**indicadores de qualidade**)
 - Possibilitar que os colaboradores internos possam visualizar os dados graficamente para traçar estratégias de negócio (**indicadores de negócio**)
 - Controlar o acesso a dados sigilosos
 - Não restringiu plataformas de acesso, apenas que seu uso deve ser apenas para colaboradores internos.
 - Os lotes recebidos pela empresa são em arquivos com extensão xlsx.

## Histórias do Usuário

Para entender a necessidade do cliente, discutiu-se os possíveis casos de uso dos usuários. O projeto delimita a utilização do software em dois usuários distintos: 
 - **Administrador**: pessoa que controla a inserção e visualização dos dados e o controle de acesso de usuários à plataforma
 - **Usuário com acesso restrito**: todos os funcionários internos da organização autorizados a visualizar os indicadores de qualidade e negócio, cadastrados pelo administrador

![](https://i.imgur.com/gIbZb82.jpg)


## Diagrama de Caso de Uso

**Diagrama do Administrador:**
![](https://i.imgur.com/3N5OMN5.jpg)


**Diagrama do Funcionário:**
![](https://i.imgur.com/04Pnz89.jpg)



## Backlog do Produto


# Arquitetura
O modelo de arquitetura de software poderá ser alterado conforme as necessidades do projeto, mas a princípio será utilizado o modelo MVC, trabalhando com a linguagem Python nos tratamentos de dados, e a linguagem HTML com framework Boostrap na interface. A escolha do framework Bootstrap, deve-se ao fato desse permitir a construção de uma interface responsiva que pode se adaptar automática a diferentes tipos de suporte.

# Código

**Demonstração da linguagem Python:**









> Sábado, 12 de Maio de 2020, 10:53  
> feito em [hackmd.io](https://hackmd.io)
