# SuperTrunfoInt

# 🃏 Cartas de Países - Jogo de Comparação

Este projeto é um programa em linguagem C que simula um jogo de comparação de cartas de países. Cada carta possui informações como população, área, PIB, número de pontos turísticos e densidade demográfica.

O jogador pode cadastrar duas cartas e escolher, através de um menu interativo, qual atributo será usado para comparar e definir o país vencedor.

---

## Funcionalidades

- Cadastro de informações de dois países.
- Cálculo automático da densidade demográfica.
- Menu interativo para escolher o atributo de comparação.
- Regras de comparação:
- A maioria dos atributos: vence quem tiver o maior valor.
- Para "densidade demográfica", **vence quem tiver o menor valor.**
- Exibição clara dos dados e do resultado da comparação.
- Mensagem de empate caso os valores sejam iguais.

---

Como usar
✅ Ao executar o programa:
-O programa solicitará os seguintes dados para cada carta:

Nome do país
População
Área (em km²)
PIB (em trilhões)
Número de pontos turísticos

-Após cadastrar, aparecerá o menu de comparação:
=========== MENU DE COMPARAÇÃO ===========
Escolha o atributo para comparar:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Demográfica (Menor vence)

-Escolha uma opção digitando o número correspondente.

-O resultado da comparação será exibido mostrando:
Nome dos países
Atributo utilizado
Valores de cada país
Qual carta venceu ou se houve empate.

EXEMPLO DE USO:
1. Entrada de dados:

Cadastro da Carta 1:
Nome do País: Brasil
Populacao: 214000000
Area (km^2): 8515767
PIB (em trilhoes): 1.9
Numero de pontos turisticos: 20

Cadastro da Carta 2:
Nome do País: Japão
Populacao: 125000000
Area (km^2): 377975
PIB (em trilhoes): 4.9
Numero de pontos turisticos: 35

2. Escolhendo a opção 3 (PIB):
=========== RESULTADO DA COMPARACAO ===========
Paises: Brasil x Japão
Atributo: PIB (trilhoes)
Brasil: 1.90 | Japão: 4.90
Vencedor: Japão
