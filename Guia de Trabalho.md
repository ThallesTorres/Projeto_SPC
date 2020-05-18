# Guia de Trabalho

- Os arquivos da SPRINT atual devem ser colocados na respectiva pasta  
- Nomear os arquivos de análise das tabelas da seguinte forma:  
```
    analise_nome-da-tabela
    analise_STG_FTT_ITT
```
- Indicar no arquivo requirements.txt da respectiva SPRINT, as bibliotecas utilizadas. Se a biblioteca já constar no arquivo, não alterar  
- Salvar pelos menos uma imagem do gráfico mais importante da análise:  
```
    img_nome-da-tabela_numero_.jpg
    img_STG_FTT_ITT_1.jpg
```
- Outras regras surgirão no decorrer das SPRINTs

## O TIME

**Product Owner:** Guilherme
```
    Responsável por:  contatar o cliente, levantar requisitos e estórias do usuário com o cliente,
                      definir tarefas e entregas dos sprints junto ao cliente,
                      definir o nível de dificuldade junto ao Scrum Master
```
**Scrum Master:** Diego
```
    Responsável por:  prepar documentação, delegar tarefas e preparar fluxo de trabalho,
                      dar assistência a todos os membros, fazer pontes internas,
                      definir o nível de dificuldade junto ao Product Owner
```
**Developers:** Diego, Guilherme, João, Rodrigo, Thalles, William

## SPRINT 3

### IMPORTANTE:
>O andamento e as rotas definidas nessa sprint poderão alterar o escopo desse trabalho, com possível redesenho das sprints e das histórias do usuário  

**Guilherme**  
**`Teste Principal`** Testar a possibilidade de chamar frames de HTML dentro das páginas  
```
    Necessário para determinar a utilização do plotly nessa Sprint
```
**`Teste Opcional`** Caso não seja possível, testar a possibilidade de gerar HTMLs com a biblioteca Dash  
Desenvolver HTML  
```
    Conforme layout das páginas (Wireframes) e a padronização das informações
```

**Diego**  
Padronizar legendas, cores e organização  
Desenvolver layout das informações  

**O Time**  
**`atrasado`** Resolver tarefas pendentes da Sprint anterior  
Quebrar gráficos (dividí-los) para melhorar a visualização das informações  
Ver possibilidade de utilização da biblioteca plotly  
```
    Precisa de teste e aprovação do Guilherme para dar procedimento a essa tarefa
    (Guilherme testará a possibilidade de chamar frames de HTML dentro das páginas)
```
Gerar executável do tratamento dos gráficos  
```
    IMPORTANTE: Deve ser apenas um para o grupo
    OPÇÃO 1: Gerar executável que apenas trate os dados, sem interface
    OPÇÃO 2: Verificar a possibilidade de gerar uma interface que permita a inserção dos dados que serão analisados
```

## SPRINT 1 e SPRINT 2

**Guilherme (STG_FNT_ITT)**  
`único` ~~Contar CNPJs válidos~~  
```
    Precisa de revisão
    Métricas: preenchimento total, valores válidos, valores inválidos
```
`único` Contar nome social e razão social com valores únicos  
```
    Levantar métricas: valores iguais, valores diferentes, preenchimento total, filtrar com os CNPJs válidos
```
*`comum`* Verificar recência dos dados  
*`comum`* ~~Contar linhas com campos completos e desprezar os invalidados nas análises~~  
```
    Gerar gráficos apresentando a porcentagem de preenchimento das colunas
```

**Diego (STG_MVT_CRD)**  
*`comum`* ~~Contar linhas com campos completos e desprezar os invalidados nas análises~~  
*`comum`* ~~Validar as modalidades~~  
*`comum`* Verificar recência dos dados  
```
    Precisa de revisão
```
`único` ~~Contar número de clientes únicos por modalidade~~  
`único` ~~Contar número de movimentações por modalidade~~  
`único` ~~Valor das parcelas do saldo utilizado por modalidade~~  
`único` ~~Valor total  das faturas no cartão de crédito~~  
`único` ~~Valor mínimo das faturas no cartão de crédito~~  

**Thalles / William (STG_OPR_ITT)**  
*`comum`* ~~Contar número de linhas com todos os campos preenchidos e deprezar na análise as invalidadas~~  
*`comum`* ~~Validar as modalidades~~  
*`comum`* Verificar recência dos dados  
```
    Precisa de revisão
```
`único` ~~Número de operações por modalidade~~  
`único` ~~Comparar valor total e valor não pago do contratado da modalidade (C01/Consócio)~~  
`único` ~~Número de parcelas por modalidade~~  

**João / Rodrigo (STG_PGT)**  
*`comum`* Contar número de linhas com todos os campos preenchidos e deprezar na análise as invalidadas  
*`comum`* Validar as modalidades  
```
    Código pronto, precisa só aplicar
```
*`comum`* Verificar recência dos dados  
```
    Código pronto em revisão, mas ainda sem aplicação nessa tabela
```
`único` ~~Número de pagamentos por modalidade~~  
`único` Número de registros vencidos por modalidade  
`único` ~~Valor total de pagamentos por modalidade~~  
