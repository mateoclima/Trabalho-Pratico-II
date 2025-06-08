# Simulador de Atendimento Hospitalar por Classificação de Risco (Protocolo de Manchester)
## Descrição do Projeto
Este projeto consiste no desenvolvimento de uma aplicação em linguagem C para gerenciar o atendimento em um plantão psicológico. 
O sistema tem como objetivo principal utilizar listas lineares de forma funcional, com foco no armazenamento, manipulação e exibição de dados relacionados a este contexto, integrando teoria e prática. 
Os atendimentos seguem a ordem de chegada (primeiro a chegar, primeiro a ser atendido). 
O sistema também deve manter um registro histórico dos atendimentos realizados, com controle por estudante

## Funcionalidades Implementadas:
- [ ] Cadastrar paciente
- [ ]	Classificar paciente na triagem com prioridade (1 a 5) e inserir na fila
- [ ]	Atender próximo paciente com maior prioridade
- [ ]	Visualizar fila de espera atual por ordem de prioridade
- [ ] Gerar relatório de atendimentos com:
        - a. Pacientes atendidos por prioridade
        - b. Tempo médio de espera por categoria
        - c. Total de pacientes por cor/nível de risco

## Estruturas de Dados Utilizadas


## Estrutura dos Arquivos do Projeto

O projeto está organizado nos seguintes arquivos principais:

* `main.c`: Contém a lógica principal e o controle do sistema, gerenciando a interação do usuário com as funcionalidades.
* `fila.c`: Implementação das funções relacionadas à fila circular de espera (ex: registrar chegada, remover da fila, listar fila).
* `fila.h`: Arquivo de cabeçalho para `fila.c`, contendo as definições das estruturas de dados da fila e os protótipos das funções.
* `historico.c`: Implementação das funções relacionadas ao histórico de atendimentos (ex: registrar atendimento no histórico, consultar histórico, emitir relatório).
* `historico.h`: Arquivo de cabeçalho para `historico.c`, contendo as definições das estruturas de dados do histórico e os protótipos das funções.
* `README.md`: Este arquivo, contendo orientações sobre o projeto, autoria e instruções.
* `diario_de_bordo.pdf`: Documento com os relatos semanais do processo de desenvolvimento do projeto.

## Como Compilar e Executar

1.  **Compilação:**
    ```bash
    gcc main.c fila.c historico.c -o sistema_atendimento
    ```
2.  **Execução:**
    ```bash
    ./sistema_atendimento
    ```

Certifique-se de que todas as dependências (bibliotecas padrão do C) estejam disponíveis no seu sistema.

## Autoria

Este projeto foi desenvolvido por:

* [Bruno Pedron Rupaner]
* [Dyego Dasko]
* [Matheus José Chaves de Lima]
* [Pedro Henrique Moreira da Silva]
* [Thiago de Lima de Assis Cordeiro]
