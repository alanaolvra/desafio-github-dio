# Introdução ao Git e ao GitHub

Software de versionamento de código. Git e GitHub são diferentes.

Vantagens: controle de versão, armazenamento em nuvem, trabalho em equipe, melhorar seu código, reconhecimento.

| Comandos básicos para um bom desempenho no terminal |             |
| --------------------------------------------------- | :---------- |
| Mudar de pastas                                     | cd          |
| Listar pastas                                       | dir         |
| Criar pastas/arquivos                               | mkdir       |
| Deletar pastas/arquivos                             | del / rmdir |

### Entendendo como o Git funciona por debaixo dos panos

##### Tópicos fundamentais para entender o funcionamento do Git

* **SHA1:** Algoritmo de hash seguro, conjunto de funções hash criptografadas projetadas pela NSA. A encriptação gera um conjunto de caracteres identificador de 40 dígitos. Forma curta de representar um arquivo.

* **Objetos internos do Git:** 

- Blobs: tipo, tamanho, \0, conteúdo (metadados).

\- Trees: armazenam blobs.

\- Commits: aponta para: árvore, parente, autor, mensagem, timestamp.

* **Sistema distribuído seguro**
* **Chave SSH e Token**:

Chave SSH é uma forma de estabelecer conexão segura e encriptada entre duas máquinas.

### Primeiros comandos com Git

Git init    -   Git add   -   Git commit

##### Ciclo de vida dos arquivos no Git

| Passo a passo no ciclo de vida |        |
| ------------------------------ | ------ |
| Untracked -> staged            | add    |
| Unmodified -> modified         | edita  |
| Modified -> staged             | pronto |
| Unmodified -> untracked        | remove |
| Staged -> unmodified           | commit |

### Repositórios

* Servidor: repositório remoto

* Ambiente de desenvolvimento: repositório de trabalho – área de staging – repositório local