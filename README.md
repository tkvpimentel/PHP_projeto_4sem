# Loja de Cartas

Sistema simples em PHP orientado a objetos, executado pelo terminal, que simula a compra de cartas colecionáveis. Desenvolvido como trabalho final da disciplina, relacionando os diagramas UML com o código.

## Integrantes

- Nome 1
- Nome 2
- Nome 3

## Requisitos

- PHP 8.1 ou superior (desenvolvido com PHP 8.5)
- Nenhum framework, banco de dados ou interface gráfica

## Como executar

```bash
git clone <url-do-repositorio>
cd loja-cartas
php index.php
```

## Estrutura do projeto

```
loja-cartas/
├── src/
│   ├── Model/        Classes de domínio (Usuario, Carrinho, ItemCarrinho, Carta, Pedido, Pagamento)
│   ├── Enum/         Enumerações (StatusPedido)
│   ├── Repository/   Armazenamento em memória (substitui o banco de dados)
│   ├── Controller/   Regras do fluxo de compra (CompraController)
│   └── View/         Saída no terminal (TelaCarrinho)
├── docs/
│   └── diagramas/    Diagramas UML exportados do Visual Paradigm
├── index.php         Ponto de entrada
└── README.md
```

## Diagramas UML

| Diagrama | Arquivo |
|---|---|
| Classes | `docs/diagramas/classes.png` |
| Sequência (finalizar compra) | `docs/diagramas/sequencia.png` |
| Máquina de estados (Pedido) | `docs/diagramas/estados.png` |
| Componentes | `docs/diagramas/componentes.png` |

## Fluxo de trabalho com Git

- A branch `main` recebe código apenas por Pull Request.
- Cada tarefa é feita em uma branch própria: `feature/<nome-da-tarefa>`.
- Todo Pull Request é revisado e aprovado por outro integrante antes do merge.
- Padrão de commits:
  - `feat:` nova funcionalidade
  - `fix:` correção de erro
  - `refactor:` melhoria no código sem mudar o comportamento
  - `docs:` documentação

## Princípios aplicados

_(a preencher: SOLID, refatoração, revisão, documentação e depuração)_
