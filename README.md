# Conteúdo de Fisioterapia com Claude

Agentes de IA para criar conteúdo de fisioterapia gastando poucos créditos: ideias, roteiros de vídeo, posts e revisão ética.

## Agentes
| Agente | Modelo | Função |
|---|---|---|
| `ideias-fisio` | Haiku | Ideias e pautas de conteúdo |
| `roteirista-fisio` | Sonnet | Roteiros para Reels, TikTok e Shorts |
| `copy-fisio` | Sonnet | Legendas, carrosséis, stories e hashtags |
| `revisor-fisio` | Haiku | Revisão técnica e ética (COFFITO) |

## Como usar
1. Abra uma sessão do Claude Code com este repositório.
2. Preencha seu perfil no `CLAUDE.md` (uma vez só).
3. Peça por etapa, por exemplo:
   - "use o ideias-fisio para 10 ideias sobre dor lombar"
   - "use o roteirista-fisio para a ideia 3"
   - "use o copy-fisio para a legenda desse roteiro"
   - "use o revisor-fisio no texto final"

## Estrutura
```
CLAUDE.md            # regras de economia e perfil profissional
.claude/agents/      # os 4 agentes
```
