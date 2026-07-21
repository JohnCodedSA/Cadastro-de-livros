# Sistema de Cadastro de Livros e Empréstimos (Linguagem C)

Projeto focado no gerenciamento de uma biblioteca, cobrindo desde estruturas estáticas básicas até alocação dinâmica de memória e modularização de código em C.

---

### 📌 Evolução do Código

O repositório contém a evolução progressiva da aplicação:

1. **`livraria1.c`**: Implementação básica com `structs` e `arrays` estáticos para cadastro e listagem.
2. **`livraria2.c`**: Introdução de gerenciamento de empréstimos e uso de alocação dinâmica (`malloc`/`calloc`) para manipulação de memória.
3. **`main.c`**: Refatoração completa com arquitetura modular (divisão em funções especializadas, ponteiros e passagem de parâmetros por referência).

---

### 🛠️ Tecnologias e Conceitos Aplicados

- **Linguagem:** C
- **Manipulação de Memória:** `malloc`, `calloc`, `free` (prevenção de memory leaks)
- **Estrutura de Dados:** `struct` para representação de livros e empréstimos
- **Boas Práticas:** Limpeza de buffer de entrada (`getchar`), tratamento de acentuação (`locale.h`) e modularização em funções
