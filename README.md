# DesafioArray

# Descrição

O DesafioArray tem como objetivo a implementação de uma lista de funcionários, permitindo ao usuário cadastrar novos funcionários, validar IDs duplicados, e realizar o aumento salarial de um funcionário com base em uma porcentagem fornecida pelo usuário.

# Funcionalidades

Cadastro de funcionários com ID, Nome e Salário.

Validação de ID duplicado.

Consulta e seleção de funcionários pelo ID.

Aumento salarial baseado em uma porcentagem informada pelo usuário.

Exibição da lista de funcionários após as alterações.

# Como funciona

O programa solicita ao usuário o número de funcionários a serem cadastrados.

1. Para cada funcionário, são coletados os seguintes dados:

        * ID (com validação para evitar duplicatas);
    
        * Nome;
        
        * Salário.

2. Após o cadastro, o programa solicita um ID para aumentar o salário.

3. Caso o ID seja encontrado, é solicitado um percentual de aumento, e o salário é atualizado.

4. Ao final, a lista de funcionários é exibida com os dados atualizados.

# Estrutura do Código

Classe Program: Contém a lógica principal do programa.

    *  Classe Funcionario (presumida): Representa os dados e comportamentos do funcionário.

    *  Métodos auxiliares:

    * hasID(List<Funcionario> list, int id): Verifica se o ID já existe na lista.

    *  posicao(List<Funcionario> list, int id): Retorna a posição do funcionário na lista.
