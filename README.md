# trabalhoSQL

Trabalho em SQL 


## 1ª Questão
Selecione todos os dados dos países da tabela_paises;

``` sql
selecione * da tabela_paises
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/48c11b42-a823-4f53-aae9-15a47bcdecf4)


## 2ª Questão
Selecione todas as cidades cujo país seja brasil;

``` sql
selecione cidade na tabela_paises onde pais =  ' Brazil
```
## Resultado esperado

![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/c84aeebb-46d7-40a9-89f5-7e01bc9e175d)


## 3ª Questão
Selecione todas as cidades cujo(estado) é ceará;
```sql
selecione cidade na tabela_paises onde regiao = ' Ceará '
```
## Resultado esperado

![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/0789e2b6-b293-4324-8e0d-582f8fb2dd46)


## 4ª Questão
Utilize a função count para saber quantas regiões(estados) existem na China,
utilize também o group by;
```sql
select count(regiao) from tabela_paises where pais = ' China ' group by regiao
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/9079bc70-35f6-47c5-bcaf-8c205bf2062f)


## 5ª Questão
Quais regiões, diferentes, existem no Canadá?
```sql
selecione contagem(região distinta) da tabela_paises onde pais = ' Canadá '
```

## Resultado esperado
##![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/d5e09194-c7b6-4ef0-92d3-70b59747eaec)


## 6ª Questão
Quantos países diferentes existem na tabela ' tabela_paises ' ;
```sql
selecione pais distintos da tabela_paises
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/f9c19047-abaf-4485-a71b-6369b14b1701)


## 7ª Questão
Quantas cidades diferentes existem no Brasil;
```sql
selecione cidade distinta da tabela_paises onde pais = ' Brasil '
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/be11218d-0871-4502-8923-b562445d6951)


## 8ª Questão
Selecione os países e quantas regiões cada país possui;
```sql
selecione pais,count(regiao) do grupo tabela_paises por pais
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/1cd811fe-2262-4ac0-8d11-bffc2908e1db)


## 9ª Questão
Quantas pessoas com nome começando em ' João ' não existem no banco?
```sql
selecione contagem(nome) da tabela_paises onde nome como ' João% '
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/43ca7154-a26a-494b-a76d-4fde473af634)


## 10ª Questão
Quantas pessoas têm o nome John?
```sql
selecione contagem(nome) da tabela_paises onde nome = ' João '
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/46a9c2e0-c6f5-406b-b883-151cc395b19e)


## 11ª Questão
Ordenar os nomes dos países sem reprodução em ordem alfabética;
```sql
selecione pais distintos da tabela_paises ordene por pais ASC
```
## Resultado esperado
![image](https://github.com/K4aro0lineFranca/trabalhoSQL/assets/117689067/baec243f-c2f0-4079-8386-b9a3a453440a)

