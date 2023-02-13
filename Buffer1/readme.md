# Easy Stats

> items Necessarios:
> Tabela, Vida-jogador, Stamina-Jogador, Munição-Jogador, Está em Movimento?, Velocidade-jogador, Está Vivo?.

> Tabela: []
> Quando o usuario Solicitar uma informação, a tebela ira retornar essa infomação 

>Vida-Jogador/Stamina-Jogador/Munição-Jogador/Está em Movimento?/Velocidade-jogador/Está Vivo?: []
>Vai Retornar Informações do Element "Player" para o Dev

IsCustomable? = False
IsOpenSource? = True
IsEasyToCustomable = True

1- a tabela vai esperar o dev solicitar uma informação
2- o usuario vai solicitar um informaçâo
3- a tabela vai ver se essa informção existe
4- vai retornar a informação em valor para o player

[if] [2] == true [then]
    [1] -> [2] -> [3] -> [4]
[else]
    [1] -> [1]
[end]

stack = eventos, informações, tabelas, funções.
