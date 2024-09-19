# MeuPrimeiroProjeto
 Instruções do Jogo: Pedra, Papel e Tesoura
Objetivo:
O objetivo do jogo é vencer o computador em uma série de rodadas de Pedra, Papel e Tesoura, um jogo clássico onde:

Pedra vence Tesoura
Tesoura vence Papel
Papel vence Pedra
Como Jogar:
Escolha sua jogada: Você deve escolher entre as três opções:

Pedra
Papel
Tesoura
Iniciar o jogo: O jogo solicitará que você faça sua escolha. Você pode digitar "pedra", "papel" ou "tesoura".

Vencedor da rodada:

Após fazer sua escolha, o computador fará sua escolha aleatória.
O resultado da rodada será exibido:
Se você e o computador escolherem a mesma opção, será um empate.
Caso contrário, o vencedor será anunciado.
Continuar ou sair: Após cada rodada, você pode escolher jogar novamente ou digitar "sair" para encerrar o jogo.

Como o Jogo Funciona
Lógica do Jogo:
O jogo utiliza um loop while que permite jogar várias rodadas até que o usuário decida sair.
As escolhas do usuário e do computador são comparadas para determinar o vencedor.
Estrutura do Código:
Importação de Bibliotecas: O código importa o namespace System para permitir a entrada e saída no console.

Criação de um Array: Um array chamado opcoes armazena as três opções possíveis: "pedra", "papel" e "tesoura".

Entrada do Usuário: O programa solicita que o usuário insira sua escolha, que é convertida para minúsculas para evitar problemas de capitalização.

Verificação de Entrada:

Se o usuário digitar "sair", o jogo termina.
Se a entrada do usuário não estiver no array de opções, uma mensagem de erro é exibida e o loop continua.
Escolha do Computador: O computador seleciona aleatoriamente uma opção usando a classe Random.

Comparação de Resultados: As escolhas são comparadas em condições if para determinar o vencedor e exibir o resultado no console.

Como Foi Construído o Jogo
Linguagem: O jogo foi implementado em C#.
Algoritmo: Utiliza um algoritmo simples de comparação baseado nas regras do jogo.
Interatividade: O programa é interativo, permitindo que o usuário insira suas escolhas diretamente no console.
Estrutura: O código é modular, permitindo fácil leitura e manutenção.
Execução
Para jogar, você precisa ter um ambiente de desenvolvimento C# (como Visual Studio ou Visual Studio Code) instalado em seu computador. Basta copiar o código, colar em um novo arquivo, compilar e executar.

Se precisar de mais informações ou detalhes, fique à vontade para perguntar!
