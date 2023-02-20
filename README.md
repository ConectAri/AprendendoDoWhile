# AprendendoDoWhile

Aqui está um exemplo de código que cria uma classe simples em Java que oferece as opções de Cadastro, Imprimir e Sair,
solicita ao usuário a entrada de um nome quando a opção 1 for escolhida e exibe o nome digitado na tela.
Ele também inclui um loop do-while para repetir as opções para o usuário até que a opção Sair seja escolhida:

O programa começa criando um objeto Scanner para ler a entrada do usuário a partir da linha de comando.

Em seguida, ele entra em um loop do-while que exibe as opções disponíveis para o usuário e lê a entrada do usuário para determinar a opção escolhida.

O switch case é usado para determinar qual ação executar com base na opção escolhida pelo usuário.

Se o usuário escolher a opção 1, o programa solicita o nome do usuário e o armazena em uma variável nome. Em seguida, ele exibe o nome na tela.

Se o usuário escolher a opção 2, o programa simplesmente exibe uma mensagem informando que a opção Imprimir foi selecionada.

Se o usuário escolher a opção 9, o programa exibe uma mensagem informando que a opção Sair foi selecionada e sai do loop.

Se o usuário escolher uma opção inválida, o programa exibe uma mensagem informando que a opção é inválida.

Por fim, o programa fecha o objeto Scanner.

A opção while (opcao != 9); no final do programa cria um loop que continua a ser executado enquanto o valor da variável opcao for diferente de 9.
Isso significa que o loop continuará sendo executado até que o usuário escolha a opção 9, que normalmente é uma opção de saída do programa.

A linha scanner.close(); é usada para fechar o objeto Scanner criado anteriormente. Isso é importante porque, se você não fechar o objeto Scanner,
ele continuará a consumir recursos do sistema e pode levar a problemas de desempenho ou até mesmo a erros no seu programa.

Exemplo no código:
 } while (opcao != 9);
        scanner.close();
