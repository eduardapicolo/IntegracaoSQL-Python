# Menu de Alteração de Valores

## 📌 Descrição

Este sistema em Python permite a alteração de valores e nomes de colunas em uma tabela de banco de dados Oracle. Ele fornece um menu interativo para que o usuário possa navegar entre as opções e modificar os dados conforme necessário.

## 🚀 Funcionalidades

- 🔗 **Conexão com banco de dados Oracle**
- 📌 **Alteração de valores de uma coluna específica**
- ✏️ **Alteração do nome de uma coluna**
- 🔄 **Navegação interativa entre as opções**

## 🔄 Fluxo do Programa

1. O sistema tenta estabelecer uma conexão com o banco de dados.
2. Exibe o menu inicial de alteração de valores.
3. O usuário pode escolher entre alterar valores de uma coluna ou renomear uma coluna.
4. O sistema processa a alteração no banco de dados.
5. O processo se repete até que o usuário opte por sair.

## 🏗 Estrutura do Código

- `tela_alteracao()`: Exibe o menu inicial de alteração.
- `navegarAlteracoes(tela_atualA)`: Gerencia a navegação entre as telas de alteração.
- `tela_Avalores()`: Permite a alteração dos valores de uma coluna específica.
- `tela_Anome()`: Permite renomear uma coluna da tabela.
- `mainAlteracoes()`: Inicializa o sistema e gerencia o fluxo de interação com o usuário.

## ⚠️ Observação

- Certifique-se de que as credenciais do banco de dados estão corretas.
- O usuário deve possuir permissões para realizar alterações nas tabelas do banco.
- O código usa `f-strings`, portanto, é compatível com Python 3.6 ou superior.

🚀 **Sistema pronto para facilitar suas alterações no banco de dados!**
