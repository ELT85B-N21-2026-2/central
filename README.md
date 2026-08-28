# Solicitações de inclusão em times — `ELT85B-N21-2026-2`

Este repositório é o **ponto único de entrada** para solicitações de inclusão manual de alunos em times (grupos) da organização **`ELT85B-N21-2026-2`**.

Toda solicitação deve ser feita por meio de uma **issue**, usando o formulário disponível. Issues em branco estão desativadas.

## Para alunos

1. Abra uma nova issue: [**Criar solicitação**](../../issues/new/choose).
2. Selecione o formulário **"Solicitar inclusão em time"**.
3. Preencha:
   - **Grupo (slug do time):** escolha o slug do seu grupo (de `grupo-a` a `grupo-j`).
   - **Seu username do GitHub:** informe seu nome de usuário, sem o `@`.
   - Marque a confirmação de que o username está correto.
4. Envie a issue e aguarde. Um administrador irá adicionar você ao time e fechar a issue.

> **Atenção:** confira seu username antes de enviar. Um username incorreto atrasa a inclusão.

## Para administradores

Ao receber uma nova issue de solicitação:

1. Confira o **slug do grupo** e o **username** informados na issue.
2. Acesse a aba de membros do time correspondente, substituindo `<slug>` pelo grupo informado:
   ```
   https://github.com/orgs/ELT85B-N21-2026-2/teams/<slug>/members
   ```
   Exemplo, para `grupo-a`:
   ```
   https://github.com/orgs/ELT85B-N21-2026-2/teams/grupo-a/members
   ```
3. Adicione o username informado ao time.
4. **Feche a issue** confirmando a inclusão.

O padrão de slug dos grupos vai de `grupo-a` até `grupo-j`.

## Estrutura do repositório

```
.
├── README.md
└── .github/
    └── ISSUE_TEMPLATE/
        ├── solicitar-time.yml   # Formulário de solicitação de inclusão
        └── config.yml           # Desativa issues em branco
```
