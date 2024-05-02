<h1>Ping Pong</h1>

Este programa cria três goroutines: uma para enviar "ping" para um canal, outra para enviar "pong" para o mesmo canal e a última para ler do canal e imprimir o valor. A execução alternada de "ping" e "pong" é garantida pela forma como as goroutines e os canais funcionam em Go.