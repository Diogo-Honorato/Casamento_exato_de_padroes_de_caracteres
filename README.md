A Busca Mágica pela Substring Perdida

Em um reino encantado onde a magia permeia todas as coisas, uma antiga profecia foi revelada.
Dizia-se que uma poderosa substring, capaz de conceder imenso poder a quem a dominasse, estava
perdida nas profundezas das palavras místicas. Os sábios do reino, temerosos dos perigos que essa
substring poderia desencadear nas mãos erradas, convocaram os mais habilidosos buscadores para
recuperá-la.

Você, um jovem aprendiz de magia, foi escolhido para embarcar nessa jornada. O Grande Mago,
guardião dos segredos ocultos, lhe confiou uma tarefa crucial: encontrar a substring perdida dentro
de uma série de palavras encantadas.

Você recebeu um pergaminho mágico contendo uma string misteriosa e a substring que deve
ser buscada. Além disso, foram-lhe concedidas N pergaminhos adicionais, cada um contendo um
intervalo de palavras a serem investigadas. Se a substring estiver presente em uma palavra dentro
do intervalo indicado, você deve revelar sua localização.

Mas cuidado! As palavras encantadas podem se ocultar em lugares sombrios e intricados, e
somente os mais astutos e habilidosos serão capazes de desvendar seus segredos.

Com sua varinha mágica em mãos e sua mente afiada, você parte em uma jornada pelo reino,
enfrentando desafios e perigos, na busca pela substring perdida. Será você capaz de decifrar os
mistérios das palavras encantadas e encontrar o tesouro oculto antes que caia nas mãos erradas? A
aventura aguarda!

Input

A primeira linha de entrada contém uma string de tamanho n, a segunda linha contém uma
string de tamanho m, a terceira linha contém um inteiro k: o número de queries.
Após isso, a entrada possui k linhas descrevendo os queries. Cada linha contém dois inteiros a,
b: o intervalo começa em a, termina em b

Output
Para cada querie, imprima sim caso a substring esteja presente e nao caso contrário.
Exemplo

Entrada:

abbaab
ab
3
1 4
3 5
2 6

Saída:

sim
nao
sim

Na tela, o programa deve imprimir apenas os tempos de usuário e os tempos de sistema para
comparação. Para avaliação do tempo, utilize as funções getrusage e gettimeofday.
