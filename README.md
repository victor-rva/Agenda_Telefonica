# Agenda Telefônica

Este é um simples sistema de agenda telefônica em Python, composto por três arquivos: `clsPessoa.py`, `lstAgenda.py` e `main.py`.

## clsPessoa.py

### Classe Pessoa
A classe `Pessoa` representa uma pessoa na agenda telefônica e possui os seguintes métodos:

- `__init__(self, nome, telefone)`: Inicializa uma nova instância da classe com um nome e um telefone.
- `get_nome(self)`: Retorna o nome da pessoa.
- `adicionar_telefone(self, telefone)`: Adiciona um novo número de telefone à lista da pessoa.
- `excluir_numero(self, numero_ser_excluido)`: Exclui um número de telefone da lista, se existir.
- `__str__(self)`: Retorna uma representação em string da pessoa.

## lstAgenda.py

### Classe Pessoa
A classe `Pessoa` em `lstAgenda.py` é semelhante à classe homônima em `clsPessoa.py`. Parece haver um engano, pois ambas têm a mesma implementação. Recomenda-se revisar e corrigir, caso necessário.

## main.py

O arquivo `main.py` contém a lógica principal do programa, incluindo menus interativos e funções para manipular a agenda telefônica.

### Funções
- `clear()`: Limpa a tela do console.
- `menu()`: Exibe o menu principal e direciona para as opções escolhidas.
- `sub_menu()`: Exibe um submenu e retorna a escolha do usuário.
- `ler_nome()`: Solicita e retorna o nome da pessoa.
- `ler_telefone(nome)`: Solicita e retorna o telefone da pessoa.
- `adicionar_novo_numero(pessoa, telefone)`: Adiciona um novo número à lista de telefones de uma pessoa.
- `alterar_agenda(nome)`: Permite ao usuário adicionar novo número, excluir a pessoa ou excluir um número existente.
- `adicionar_excluir()`: Executa a lógica de adicionar/excluir da agenda.

### Execução Principal
O script principal inicia o programa chamando a função `menu()`.

**Instruções de Execução:**
1. Execute `main.py`.
2. Siga as opções do menu para adicionar ou excluir contatos da agenda telefônica.
