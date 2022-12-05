# progetto api

## Comandi
 - addent <str id_ent>
 - delent <str id_ent>
 - addrel <str id_orig> <str id_dest> <str id_rel>
 - delrel <str id_orig> <str id_dest> <str id_rel>
 - report 
 - end

## Output

L'output deve essere fornito su stdout
L'unico comando a produrre output deve essere report e nel seguente ordine:
> \<id rel1\> \<id ent1\> \<id n_rel1\>; \<id rel2\> \<id ent2\> \<n rel_2\>; ...

se vengono rimosse tutte le relazioni con un dato id, esso non deve comparire nei successivi report
se non ci sono relazioni l'output deve essere:
> none
L'ordine è dato dall'ordine dei caratteri ASCII (- \< 1 \< A \< _ \< a).
 
## Input

L'input deve essere fornito su stdin
I parametri sono separati da spazi.

## Altro
sono ammesse relazioni di entità su se stesse
comandi con entità non esistenti devono essere ignorati
