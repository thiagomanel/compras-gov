# compras-gov
Projeto que analisa os dados do TCU.

## Problemas com os dados

* Licitações cujo "valor estimado" do item, não foi definido
* Compras em lote (Contratos que atendem mais de um item de uma licitação) inviabilizam a fiscalização dos preços praticados por item. O ideal seria que, como na Licitação, os preços em Contratos fossem separados por item.
* Algumas licitações referenciam anexos que não estão disponíveis no comprasnet e dificultam a fiscalização das licitações
* Existem casos onde a licitação foi feita para apenas um item e foram gerados mais de 1 contrato para esta licitação
* Algumas licitações para N itens tem os contratos associados informando o preço para 1 item ao invés do total, enquanto outas apresenta o total

## Problemas no site

* O link para as Licitações de um determinado material está incorreto. Um exemplo: O link a seguir é do material 'Estação de trabalho de processamento de dados' (vulgo PC) - http://compras.dados.gov.br/materiais/doc/material/000103047 Ao clicar na URL das licitações deste material, o link não tem os 3 zeros do início do código do material, por isso retorna ZERO nos resultados!
