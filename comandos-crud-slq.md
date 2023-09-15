# Comandos SLQ - Para CRUD (referência)

## Resumo
    C -> Create (Insere dados)
    R -> Read (Ler dados)
    U -> Update (Autualizar dados)
    D -> Create (Insere dados)

<!--_____________________________________-->

## Insert 
## Fabricantes 

```sql

INSERT INTO fabricantes (nome) VALUES('Asus');
INSERT INTO fabricantes (nome) VALUES('Dell');
INSERT INTO fabricantes (nome) 
VALUES('Apple'),('LG'),('Samsung'),('Brastamo')

```
<!--_____________________________________-->

## Insert 
## Produtos

```sql

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Ultrabock',
'Ultrabock Asus Intel Core i9',
6500.99,
7,
1
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Tablet Android',
'Tablet 10 Polegadas com 2s63b de armazenamento',
4999,
3,
5 
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Iphone 14 Pro Max',
'Processador bionic 15 com S12GB de armazenamento',
9999.57,
3,
5 
);

```
<!--_____________________________________-->

## Insert 
## Fabricantes 

```sql

INSERT INTO fabricantes (nome)
VALUES('Positivo'),('Microsoft');

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Xbox' ,
'Console de ultima geração...',
2500,
6,
8 
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Ultrabock' ,
'MO Ryzen 5 16Gb RAM...',
4500.37,
12,
7 
);


```