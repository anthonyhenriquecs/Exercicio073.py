# Exercicio073.py

times = ('corinthians', 'flamengo', 'botafogo', 'chapecoense', 'gremio', 'cruzeiro')
print('-='*15)
print(f'lista de times {times}')
print('-='*15)
print(f'Os 3 primeiros sao{times[0:3]}')
print('-='*15)
print(f'Os 3 ultimos são{times[-3:]}')
print('-='*15)
print(f'Em ordem alfabetica: {sorted(times)}')
print('-='*15)
print(f'O chapecoense esta na  {times.index("chapecoense")+1}ª posição')
