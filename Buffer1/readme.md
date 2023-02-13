# Easy Stats

> items Necessarios:
> Tabela, Vida-jogador, Stamina-Jogador, Munição-Jogador, Está em Movimento?, Velocidade-jogador, Está Vivo?.

> Tabela: [] <br>
> Quando o usuario Solicitar uma informação, a tebela ira retornar essa infomação 

>Vida-Jogador/Stamina-Jogador/Munição-Jogador/Está em Movimento?/Velocidade-jogador/Está Vivo?: [] <br>
>Vai Retornar Informações do Element "Player" para o Dev

IsCustomable? = False <br>
IsOpenSource? = True <br>
IsEasyToCustomable = True

1- a tabela vai esperar o dev solicitar uma informação <br>
2- o usuario vai solicitar um informaçâo <br>
3- a tabela vai ver se essa informção existe <br>
4- vai retornar a informação em valor para o player <br>

[if] [2] == true [then] <br>
    [1] -> [2] -> [3] -> [4] <br>
[else] <br>
    [1] -> [1] <br>
[end]

stack = eventos, informações, tabelas, funções.
