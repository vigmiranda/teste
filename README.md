# Teste
Resolução de Teste

1 - 

2 -

3 - 

4 - _Deadlock_
   - _Deadlock_ ocorre quando há um impasse em dois ou mais processos, sendo que um inviabiliza a execução do outro. O exemplo clássico é o de transações bancáriias, ao se tentar realizar um retirada com valor superior ao disponível, simultaneamente, à ação de deposito. Uma forma de tratar esse problema é criando estratégias de processos atômicos onde armazenamos as requisições em uma fila, e a execução de uma dependerá da conclusão da outra.
    

5 - _Stream_ e _ParallelStream_
   - _Stream_ é executado de forma serial, sendo utilizada somente uma _thread_ enquando o _ParallelStream_ utiliza mais de uma _thread_ e, ao final, faz um _join_ do que foi processad. Logo, podemos presumir que enquanto a _stream_ processa cada item de uma _collection_ unitariamente, a _parallelStream_ processa mais de um item simultaneamente, sendo assim mais rapída a conclusão. O grande problema ao se utilizar o _parallelStream_ é que dependendo da operação realizada podemos causar um impasse no processo gerando um _Deadlock_. Logo é recomendado sua utilização em grandes coleções com opereções independentes. 

Extra - 
