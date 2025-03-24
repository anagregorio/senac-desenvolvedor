
1. Crie, no seu banco de dados, a tabela abaixo, insira os valores apresentados e em
seguida escreva as consultas solicitadas abaixo.
OBS: Os valores em branco devem ser nulos no banco de dados.

<img src=lista.png>

a) Pesquise os itens que foram vendidos sem desconto. As colunas presentes no resultado
da consulta são: ID_NF, ID_ITEM, COD_PROD E VALOR_UNIT.

~~~~ sql
SELECT id_nf, id_item, cod_prod, valor_unit
FROM notas_fiscais
WHERE desconto IS NULL;
~~~~ 