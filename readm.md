# T.EX Desafio de Lógica 

Crie um array dinâmico com três posições [2,1,2]
Crie uma iteração que retorne números aleatórios entre 1 e 3
A cada retorno, altere o valor do array respectivamente
# Fase 2
Utilize as linhas já codificadas e insira em uma função
Crie uma verificação que identifica se os números do array são iguais
Se sim: escreva 'Porta 1: aberta'
Se não: escreva 'Tente de novo!'
# Fase 3
Crie uma variável de controle para acumular a quantidade de vezes que os números se repetem
Crie uma variável que armazene o valor do último sorteio
Compare a valor do último sorteio com o valor do sorteio atual
Se os valores forem iguais: escreva 'Porta (x)' : aberta
Se os valores forem diferentes: escreva 'Tente de novo' (Com a exceção do resultado ser de números iguais)

**Descrição do algoritmo desenvolvido:** A cada chamada de função, são sorteados 3 números consecutivos , Cada vez que é sorteado um grupo de números, é verificado se os números são iguais ou se o ultimo sorteio é igual ao atual, a cada coincidência abre uma porta. Ao abrir 3 portas, o jogo finaliza.
