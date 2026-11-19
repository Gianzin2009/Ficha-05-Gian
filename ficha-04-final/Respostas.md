## Pergunta 3

Quando acrescentamos uma carta, aparecem dois pedidos no separador Network: primeiro o `OPTIONS` e depois o `POST`.

O `OPTIONS` é um pedido de verificação feito pelo browser para confirmar se o servidor permite a comunicação entre origens diferentes. Antes de instalar o CORS, o browser bloqueava o pedido `POST`, por isso o código da rota não chegava a ser executado e o `console.log` não aparecia no terminal.

## Pergunta 4

Na primeira versão, a carta nova ficava guardada apenas no estado do React e desaparecia ao atualizar a página com F5.

Na segunda versão, a carta ficava guardada no array do servidor, mas desaparecia quando o servidor era reiniciado.

Na terceira versão, a carta fica guardada no ficheiro `cartas.json`, mantendo-se depois de atualizar a página ou reiniciar o servidor.