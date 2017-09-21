# Teste
Resolução de Teste

1 - 

2 -

3 - 

4 - Deadlock
   - Deadlock ocorre quando à um impasse em dois ou mais processos, sendo que um inviabiliza a execução do outro. O exemplo clássico é o de transações bancarias ao se tentar realizar um retirada com valor superior ao disponível simultaneamente a ação de deposito. Uma forma de tratar esse problema e criando estrategias de processos atômicos aonde armazenamos as requisições em uma fila, e a execução de uma depende da conclusão da outra.
    

5 - Stream e ParallelStream
   - Stream é executado de forma serial sendo utilizada somente uma thread enquando o ParallelStream utiliza mais de uma thread e ao final faz um join do que foi processado, logo podemos presumir que enquanto a stream processa cada item de uma collection unitariamente a parallelStream processa mais de um item simultaneamente, sendo assim mais rapída será sua conclusão. O grande problema ao se utilizar o parallelStream é que dependendo da operação realizada podemos causar um impasse no processo gerando assim um Deadlock, logo é recomendado sua utilização em grandes coleções com opereções independentes. 

Extra - 
