# A4-StringBuffer
Strings

Definição

A classe String possui uma importante característica, que é ser imutável. Isso quer dizer que uma vez atribuído um valor literal para a variável, existirá uma memória, só que sem nenhum objeto apontando para si. Assim, se você construir uma aplicação que modifique constantemente o valor da variável, você terá um desempenho ruim em termos de gastos de memória e de processamento.


StringBuilder

Outra classe que existe para manipular strings, e é uma boa alternativa à classe String se desejar que o conteúdo da string seja mutável.

StringBuffer

É uma boa alternativa às outras duas classes se desejar que o conteúdo seja mutável e necessite de uma aplicação thread safe.

Obs: O conceito de Thread-Safe surgi quando há a necessidade de trabalhar-se com programação concorrente, seu principal objetivo é garantir que 2 ou mais threads que estejam em “condição de corrida” não obtenham informações erradas (condição de corrida ou race condition ocorre quando várias threads desejam acessar o mesmo dado).

Thread-Safe é quando dois ou mais threads de uma classe não podem invocar métodos das classes simultaneamente.

Conceito Thread “um fluxo de controle sequencial isolado dentro de um programa". Permitem que um programa simples possa executar várias tarefas diferentes ao mesmo tempo, independentemente umas das outras.
