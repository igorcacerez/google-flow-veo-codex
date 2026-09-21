# Google Flow + Veo Codex

Plugin e skills para criar prompts, personagens, cenas, storyboards e fluxos de edição no Google Flow/Veo.

## Ativação

Instale o plugin e use `@flow` no Codex. A skill roteadora identifica se o pedido é sobre prompt, personagem, cena, storyboard, edição, pesquisa atual ou QA.

```text
@flow crie um prompt de 8 segundos para uma nutricionista em uma cozinha moderna
@flow crie um personagem recorrente com identidade consistente
@flow verifique os créditos e modelos atuais do Flow
```

## Princípios

- A base local em `references/google-flow/` é consultada antes de trabalhos de Flow/Veo.
- Preços, créditos, planos, acesso, limites e disponibilidade são dinâmicos e exigem verificação oficial atual.
- Prompts visuais são escritos em inglês por padrão; diálogos permanecem no idioma pedido.
- Logos, UI e telas factuais devem ser compostos com assets reais na edição.
- O pacote não inclui vídeos de produção, credenciais ou dados pessoais.

## Skills incluídas

`flow`, `flow-prompt`, `flow-character`, `flow-scene`, `flow-storyboard`, `flow-editing`, `flow-qa` e `flow-research`.

## Fontes e manutenção

A RAG é derivada de documentação pública do Google Flow, Google Labs e Help Center. Atualize os chunks somente após confirmar a mudança em fonte oficial. Consulte `references/google-flow/GOOGLE_FLOW_RAG_CODEX.md` e `google_flow_rag_chunks.jsonl`.

## Validação

```powershell
python $env:CODEX_HOME\skills\.system\skill-creator\scripts\quick_validate.py .\skills\flow
python $env:CODEX_HOME\skills\.system\plugin-creator\scripts\validate_plugin.py .
```

## Licença

MIT. O conhecimento do Google e suas marcas permanecem de seus respectivos proprietários.
