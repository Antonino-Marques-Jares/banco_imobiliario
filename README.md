# banco_imobiliario
a minha versão de um banco imobiliário com possibilidade de pegar emprestimo do banco

## Regras do Jogo:

1. Cada jogador começa com um salário inicial que deve ser informado ao adicionar a conta.
2. A cada volta completa, um novo mês começa e o salário é adicionado ao saldo, isso é determinado pelo programa. Após a logada do jogador basta dar o comando "proximo".
3. Jogadores podem comprar imóveis do banco ou de outros jogadores.
4. Jogadores podem pegar empréstimos com o banco de até 12 vezes, apenas um emprestimo é permitido por vez, o limite do emprestimo é de 10% sobre seus bens e com 10% de juros simples.
5. Se o saldo de um jogador ficar negativo, os imóveis serão passados ao banco para liquidar a dívida automaticamente e os imóveis voltam ao mercado, podendo ser comprado do banco.
6. O objetivo é acumular a maior número de imóveis evitando a falência.
7. Será decretado a falência do jogador que mesmo somando saldo e total de imóveis ainda faltar dinheiro para quitar as dívidas. Neste caso o jogador terá sido desclassificado.

## Lista de preços:

Resort: 500
Hotel: 300
Guincho: 800
Restaurante: 250
Pedagio: 25

## Comandos Disponíveis no prompt do Banco:

**adicionarConta <nome> <salario>**: Adiciona uma nova conta com o nome e salário especificados.
Exemplo: adicionarConta Nino 2000

**proximo**: Passa para o próximo jogador e atualiza o mês após uma volta completa na lista de jogadores.
Exemplo: proximo

**extrato <nome>**: Exibe o extrato da conta especificada.
Exemplo: extrato Nino

**extratoDeTodos**: Exibe o extrato de todas as contas inclusive do Banco
Exemplo: extratoDeTodos

**comprarImovel <compradorNome> <vendedorNome> <imovelNome> <valor>**: Compra um imóvel do vendedor pelo valor especificado.
Exemplo: comprarImovel Nino Banco hotel1 2000"

**transferir <remetenteNome> <destinatarioNome> <valor>**: Transfere um valor de uma conta para outra.
Exemplo: transferir Nino Ana 500"
