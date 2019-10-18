# niver_card: Gerador de cartão com a lista de aniversariantes do mês

## Execução no terminal:
$ python niver_card.py --save

### Para montar sua lista execute:

$ python nivercard.py --lista 'pessoa1 02-ago' 'pessoa2 01 out'

### Ou ainda:

$ python nivercard.py -l 'pessoa1 02-ago' 'pessoa2 01 out'


## Execução como modulo

import niver_card

niver_card.main(save=True,aniversariantes=[u'João 2 Ago',u'Joaquim2 7 Ago'])
