# Gabi na Fisio — bastidores de produção

Agentes de IA para o perfil Gabi na Fisio: pautas, pesquisa de evidências, roteiros, carrosséis e revisão — gastando poucos créditos.

## Agentes
| Agente | Modelo | Função |
|---|---|---|
| `ideias-fisio` | Haiku | Novas pautas |
| `pesquisador-fisio` | Sonnet | Pesquisa e ficha de evidências |
| `roteirista-fisio` | Sonnet | Roteiros para Reels, TikTok e Shorts |
| `copy-fisio` | Sonnet | Carrosséis e legendas |
| `revisor-fisio` | Haiku | Revisão técnica e ética (COFFITO) |

## Como usar
1. Abra uma sessão do Claude Code com este repositório.
2. Escolha uma pauta em `pautas/README.md`.
3. Peça por etapa, por exemplo:
   - "use o pesquisador-fisio na pauta 05"
   - "use o roteirista-fisio na pauta 05"
   - "use o revisor-fisio no roteiro da 05"

## Estrutura
```
CLAUDE.md               # regras do projeto, voz e design
docs/plano-editorial.md # direção do perfil
pautas/                 # fichas de evidências e status
.claude/agents/         # os 5 agentes
```
