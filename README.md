Simulador de Caixa Eletrônico em Python
Descrição:

Este código Python simula um simples caixa eletrônico, permitindo que o usuário realize operações de depósito, saque e consulta de extrato. O sistema possui limites para o valor do saque e para o número de saques diários.

Funcionalidades:

Depósito: Permite adicionar valores ao saldo da conta.
Saque: Permite sacar valores da conta, respeitando os limites estabelecidos.
Extrato: Exibe o histórico de movimentações e o saldo atual da conta.
Limite de saques: Impõe um limite máximo de saques por dia.
Limite de valor por saque: Define um valor máximo por saque.
Como usar:

Execute o código: Execute o script Python em seu ambiente de desenvolvimento.
Selecione uma opção: O menu principal apresentará as opções disponíveis: depósito, saque, extrato e sair.
Realize operações: Siga as instruções para realizar as operações desejadas.
Estrutura do código:

Variáveis:
saldo: Armazena o saldo atual da conta.
limite: Define o valor máximo por saque.
extrato: Armazena o histórico de movimentações.
numero_saques: Contabiliza o número de saques realizados.
LIMITE_SAQUES: Define o limite máximo de saques por dia.
Funções:
A lógica principal do programa está contida em um loop while True, que permite ao usuário realizar múltiplas operações.
As opções do menu são tratadas em estruturas condicionais if-elif-else.
Melhorias futuras:

Persistência de dados: Implementar um sistema para salvar os dados da conta entre as execuções do programa (por exemplo, usando arquivos ou bancos de dados).
Taxas: Adicionar taxas para as operações de saque ou depósito.
Juros: Implementar um sistema de cálculo de juros para o saldo da conta.
Interface gráfica: Criar uma interface gráfica para o programa, utilizando bibliotecas como Tkinter ou PyQT.
Autenticação: Adicionar um sistema de autenticação para permitir que apenas usuários autorizados acessem a conta.
Contribuições:

Contribuições são bem-vindas! Se você encontrar algum bug ou tiver alguma sugestão de melhoria, por favor, abra um issue ou faça um pull request.

Autor:

Alyson Costa
