# otimizando_sistema_bancario
As funções de saque, depósito e extrato foram separados em funções. Foram criados novas funções:
- Cadastrar novo usuário (cliente);
  
- Cadastrar nova conta bancária.

# Saque
Função saque recebe os argumentos apenas por nome (keyword only). Sugestão de argumentos: valor, saldo, extrato, limite, numero_saques, limite_saques.
Sugestão de retorno: saldo e extrato.

# Depósito
Função depósito recebe os argumentos apenas por posição (positional only). Sugestão de argumentos: valor, saldo, extrato.
Sugestão de retorno: saldo e extrato.

# Extrato
Função extrato recebe argumentos por posição e nome (positional only e keyword only). 
Argumentos posicionais: saldo, argumentos nomeados: extrato.

# Criar novo usuário
O programa armazena os usuários em uma lista. Um usuário é composto por: nome, data de nascimento, cpf e endereço.
O endereço é uma string com o formato: logradouro, nro- bairro- cidade/sigla estado. O cpf deve ter apenas números.
Não pode ser cadastrado 2 usuários com mesmo cpf.

# Criar conta corrente
O programa armazena as contas em uma lista. Uma conta é composta por: agência, número da conta e usuário.
O número da conta é sequencial e inicia em 1. O número da agência é fixo: "0001".
O usuário pode ter mais de uma conta, mas uma conta pertence a apenas um usuário.
