# Gestão Financeira Pessoal

Este documento reúne os requisitos do projeto, organizados por categoria para facilitar a leitura e a evolução futura do sistema.

---

## Requisitos não funcionais

- O código deve ser modular e documentado, para facilitar a adição de funcionalidades.
- A interface deve ser simples e intuitiva.
- A interface deve estar em português de Portugal e usar euros como moeda.
- A persistência dos dados deve ser garantida por uma base de dados MariaDB.
- O tratamento de dados deve cumprir com a RGPD.
- O front-end deverá ser desenvolvido em HTML e CSS.
- O back-end deve ser programado utilizando Python 3.14.

### Regras de escrita de código

- Código em Python 3.14.
- Notação de variáveis em snake_case.

---

## Requisitos funcionais

- O sistema deve permitir criar uma conta no website, garantindo a privacidade dos dados do utilizador.
- O sistema deve permitir autenticação com email e palavra-passe, de forma segura.
- O sistema deve permitir recuperar a conta caso o utilizador se esqueça das credenciais.
- O sistema deve permitir inserir transações, para acompanhar os gastos.
- O sistema deve disponibilizar categorias de transações pré-definidas e permitir criar categorias personalizadas.
- O sistema deve permitir gerir transações de grupo, atribuindo despesas e mostrando o progresso.
- O sistema deve permitir definir objetivos de poupança.
- O sistema deve permitir inserir contribuições para cada poupança e mostrar o progresso.
- O sistema deve permitir eliminar poupanças ou marcá-las como terminadas/realizadas.
- O sistema deve permitir criar orçamentos.
- O sistema deve permitir definir orçamentos individuais por categoria (alimentação, lazer, roupa, etc.).
- O sistema deve mostrar o quão próximo o utilizador está de atingir o orçamento.
- O sistema deve gerar relatórios simples de gastos e saldos.
- O sistema deve permitir exportar os relatórios para os poder guardar noutras plataformas.
- O sistema deve permitir criar grupos para gerir finanças em conjunto.
- O sistema deve permitir inserir despesas partilhadas e dividi-las por membros específicos do grupo.