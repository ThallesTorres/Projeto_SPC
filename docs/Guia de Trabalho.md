# Guia de Trabalho
  
- Os arquivos da SPRINT atual devem ser colocados na respectiva pasta  
- Nomear os arquivos de análise das tabelas da seguinte forma:  
```
    analise_nome-da-tabela_versao_realizadores
    analise_FTT_1_guilherme
```
- Indicar no arquivo requirements.txt da respectiva SPRINT, as bibliotecas utilizadas. Se a biblioteca já constar no arquivo, não alterar  
- Salvar pelos menos uma imagem do gráfico mais importante da análise:  
```
    img_nome-da-tabela_numero_.jpg
    img_FTT_1.jpg
```
- Outras regras surgirão no decorrer das SPRINTs  



### O TIME
  
  \
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



### SPRINT 1 e SPRINT 2
  
  \
**Guilherme**
  
`único` ~~Contar CNPJs válidos~~  
`único` Contar linhas com valores únicos e deprezar repetidos  
*`comum`* Contar linhas com campos completos e desprezar os invalidados nas análises  
  
  \
**Diego**
  
`único` Contar linhas com campos completos e desprezar os invalidados nas análises  
`único` Contar número de clientes únicos por modalidade  
`único` Contar número de movimentações por modalidade  
`único` ~~Valor das parcelas do saldo utilizado por modalidade~~  
`único` Valor total  das faturas no cartão de crédito  
`único` Valor mínimo das faturas no cartão de crédito  
  
  \
**Thalles / William**
  
*`comum`* Contar número de linhas com todos os campos preenchidos e deprezar na análise as invalidadas  
`único` Número de operações por modalidade  
`único` Valor contratado e saldo devedor por modalidade  
`único` Número de parcelas por modalidade  
  
  \
**João / Rodrigo**
  
*`comum`* Contar número de linhas com todos os campos preenchidos e deprezar na análise as invalidadas  
`único` ~~Número de pagamentos por modalidade~~  
`único` Número de registros vencidos por modalidade  
`único` Valor total de pagamentos por modalidade
