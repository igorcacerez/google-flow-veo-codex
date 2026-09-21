---
title: "Google Flow RAG Knowledge Base for Codex"
language: "pt-BR"
last_verified: "2026-09-17"
scope: "Google Flow AI creative studio: video, image, Agent, Characters, models, workflows, prompting, editing, credits, policies"
source_policy: "Official Google/Google Labs sources prioritized"
warning: "Pricing, credits, model matrices, plan access and region availability are dynamic. Verify live official docs before asserting current values."
---

# Google Flow — Base RAG para Codex

Esta base foi estruturada para recuperação semântica e uso por uma IA/Codex. Ela separa fatos oficiais, práticas operacionais e alertas de volatilidade. Os tópicos foram escritos para funcionar como chunks independentes.

## 00. Instruções de uso para o Codex

Este arquivo é uma base de conhecimento operacional sobre o Google Flow, o estúdio criativo de IA do Google para vídeo, imagem e ferramentas criativas. Use-o para responder dúvidas, desenhar workflows, escolher recursos/modelos e escrever prompts.

REGRAS DE CONFIABILIDADE:
1. Priorize a documentação oficial atual do Google Flow/Google Labs sobre blogs antigos, tutoriais de terceiros ou memória.
2. Dados de preço, créditos, planos, nomes de modelos, disponibilidade regional e limites são VOLÁTEIS. Antes de afirmar valores atuais em uma tarefa conectada à internet, verifique a documentação oficial/live UI.
3. Quando fontes oficiais divergirem, não escolha silenciosamente uma delas. Diga que há divergência de rollout/documentação e recomende verificar o produto.
4. Diferencie:
   - Google Flow: estúdio criativo/filmmaking para vídeo, imagem, agentes, assets e ferramentas.
   - Google Flow Music: produto relacionado para música.
   - Google Workspace Studio / antigos Workspace Flows: automação de trabalho. NÃO é o mesmo produto.
5. Não invente botões, nomes de menus, resoluções, modelos, limites ou recursos.
6. Recursos variam por país, plano e plataforma (web/desktop/mobile).
7. Ao gerar prompts, se o usuário não pedir o contrário, prefira instruções visuais em inglês para maximizar aderência; diálogos podem permanecer em português brasileiro ou no idioma final desejado.
8. Quando houver personagem recorrente, separe identidade de cena: identidade fixa; roupa, local, pose e ação variáveis.
9. Para publicidade com interface de software real, prefira gerar a pessoa/cena com tela neutra e inserir a captura real do produto na edição. Não peça ao gerador para reconstruir UI precisa quando a fidelidade factual importa.
10. Faça prompts modulares e verificáveis. Evite parágrafos caóticos com instruções conflitantes.

ESTRUTURA DE PROMPT RECOMENDADA:
SUBJECT/CHARACTER → ACTION → ENVIRONMENT → OUTFIT/PROPS → CAMERA → LIGHTING → MOTION → STYLE → AUDIO/DIALOGUE → CONTINUITY → CONSTRAINTS.

Ao responder, informe quando uma recomendação é:
- FATO OFICIAL ATUAL;
- MELHOR PRÁTICA DERIVADA;
- RECURSO HISTÓRICO/ANTIGO;
- INCERTO OU SUJEITO A ROLLOUT.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353333?hl=en
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=instructions, codex, source-priority, prompting

## 01. O que é o Google Flow

Google Flow é o estúdio criativo de IA do Google voltado a criação e refinamento de conteúdo visual e audiovisual. O produto nasceu em 2025 como uma ferramenta de filmmaking desenhada em torno de Veo, Imagen e Gemini e evoluiu em 2026 para um estúdio criativo mais amplo.

A experiência atual combina:
- geração e edição de vídeo;
- geração e edição de imagens;
- agentes criativos;
- Characters e Avatars;
- referências/Ingredients;
- Frames to Video;
- Video Extension;
- video-to-video editing;
- Scenebuilder;
- gerenciamento de projetos, assets e coleções;
- ferramentas/miniapps criados em linguagem natural;
- modelos como Veo 3.1, Gemini Omni e a família Nano Banana.

A ideia central do Flow é trabalhar de forma iterativa: criar um asset, reutilizá-lo como referência, transformá-lo em clipe, salvar frames, continuar cenas, refinar versões e montar sequências. O Flow não deve ser tratado apenas como “text-to-video”.

**Fontes oficiais:**
- https://labs.google/fx/tools/flow
- https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates/

**Metadados:** confiança=high; dinâmico=não; tags=overview, flow, veo, gemini, nano-banana

## 02. Plataformas, idade, regiões e acesso

FATOS OFICIAIS:
- O uso do Flow exige idade verificada de 18 anos ou mais.
- O Brasil aparece na lista oficial de regiões compatíveis.
- A experiência mais completa e os recursos avançados de edição são priorizados no desktop/web.
- O Google recomenda navegador Chromium no computador.
- Existem apps móveis do Flow em regiões compatíveis; alguns recursos avançados continuam exclusivos do desktop.

ATENÇÃO: há divergência entre páginas oficiais atuais sobre acesso sem assinatura. A página pública do Flow exibe uma opção gratuita com créditos diários, enquanto a página “Get started” do Help Center ainda descreve assinatura Plus/Pro/Ultra ou Workspace qualificado como requisito. Trate isso como rollout/documentação em transição. Para respostas atuais, verifique a tela real da conta ou as páginas oficiais no momento da consulta.

O idioma português é listado como compatível, mas o próprio Google recomenda prompts em inglês para melhores resultados, especialmente em instruções complexas.

**Fontes oficiais:**
- https://labs.google/fx/tools/flow
- https://support.google.com/flow/answer/16353333?hl=en
- https://support.google.com/flow/answer/16353544?hl=en

**Metadados:** confiança=medium; dinâmico=sim; tags=access, regions, Brazil, platform, subscription

## 03. Planos e créditos

O sistema de consumo do Flow usa créditos. Os valores e políticas podem mudar rapidamente.

Conforme a documentação oficial consultada em 2026:
- há referência a 50 créditos diários do Flow;
- Plus adiciona créditos mensais;
- Pro adiciona mais créditos mensais e permite top-ups em regiões elegíveis;
- Ultra oferece volume muito maior e maior acesso/prioridade;
- contas Workspace elegíveis podem receber acesso/créditos.

CUSTOS POR GERAÇÃO OBSERVADOS NA DOCUMENTAÇÃO ATUAL:
- Veo 3.1 Lite: 10 créditos para não-Ultra; 5 para Ultra.
- Veo 3.1 Fast: 20 créditos para não-Ultra; 10 para Ultra.
- Veo 3.1 Quality: 100 créditos.
- Gemini Omni Flash 720p: 4s=7, 6s=10, 8s=12, 10s=15.
- Gemini Omni Flash 360p: 4s=4, 6s=5, 8s=6, 10s=7.
- edição de vídeo com Gemini Omni Flash: 40 créditos.
- upscale 1080p: documentação atual indica custo zero para assinantes Plus/Pro/Ultra.
- upscale 4K: reservado ao Ultra e listado como 50 créditos.

REGRA: nunca codifique esses preços como eternos. O Help Center avisa que limites e custos estão sujeitos a mudança e recomenda conferir Settings/Options no prompt box antes de gerar.

Gerações que falham não devem consumir créditos; em caso de cobrança aparente, a orientação oficial é procurar suporte.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16526234?hl=en
- https://support.google.com/flow/answer/16353333?hl=en
- https://labs.google/fx/tools/flow

**Metadados:** confiança=high; dinâmico=sim; tags=credits, pricing, plans, dynamic

## 04. Matriz de modelos de vídeo

MODELOS ATUAIS PRINCIPAIS:

Veo 3.1 Lite
- Text to Video: 4s, 6s, 8s.
- Frames to Video, primeiro frame: 4s, 6s, 8s.
- Frames to Video, primeiro + último: 4s, 6s, 8s.
- Ingredients/referências: 8s.
- Extend: 8s.
- Pode ser usado para estender clipes Veo 3.1 elegíveis.
- Não é o modelo de video-to-video editing.

Veo 3.1 Fast
- Text to Video: 4s, 6s, 8s.
- Frames: 4s, 6s, 8s.
- Ingredients: 8s.
- Não é o caminho principal para edição video-to-video.
- A matriz atual do Help Center deve ser verificada porque recursos mudam por rollout.

Veo 3.1 Quality
- Prioriza qualidade.
- Text to Video e Frames em durações compatíveis.
- Algumas funções de referência/edição podem não estar disponíveis nessa variante.
- Custo maior.

Gemini Omni Flash 1.1
- Text to Video: 4s, 6s, 8s e 10s.
- Frames: primeiro e primeiro+último.
- Ingredients/referências.
- Video-to-video editing de trechos de até 10s.
- Modos 720p e draft 360p.
- O 360p é útil para testar composição/movimento com menos crédito antes do upscale/final.

HEURÍSTICA:
- ideação barata/rápida: Omni 360p ou Veo Lite, se compatível com a tarefa;
- iteração e referências: selecione o modelo que suporta Ingredients/Frames;
- edição de vídeo existente: Omni Flash;
- final de alta qualidade: gere/refine o take aprovado e faça upscale quando disponível;
- antes de decidir, confirme a matriz dentro do produto.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16352836?hl=en
- https://support.google.com/flow/answer/16526234?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/

**Metadados:** confiança=high; dinâmico=sim; tags=models, veo-3.1, omni, decision-tree

## 05. Modelos de imagem

O Flow integra geração e edição de imagens ao mesmo projeto. Em 2026, a família Nano Banana é usada para imagem.

A documentação atual cita:
- Nano Banana Pro: foco em designs complexos, alta precisão e controle profissional.
- Nano Banana 2 Lite: eficiência e boa qualidade com menor custo/maior disponibilidade.
- Nano Banana 2: opção padrão rápida e de alta qualidade em determinados contextos.

Imagens podem ser:
- assets independentes;
- frames de início/fim;
- Ingredients/referências;
- base para criação de personagens;
- etapas intermediárias para storyboard e continuidade.

WORKFLOW RECOMENDADO:
1. Gere/edite primeiro uma imagem estável do personagem ou produto.
2. Limpe fundo e elementos irrelevantes.
3. Use a imagem aprovada como referência/Ingredient ou Character.
4. Anime apenas depois de estabilizar identidade, composição e estilo.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16352836?hl=en
- https://support.google.com/flow/answer/16935308?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/

**Metadados:** confiança=high; dinâmico=não; tags=image, nano-banana, assets, storyboard

## 06. Modo Agente

O Agent do Google Flow é um colaborador criativo integrado com contexto do projeto.

CAPACIDADES:
- brainstorming;
- refino de prompt;
- sugestões criativas;
- geração de múltiplas variações;
- geração de imagem e vídeo;
- edição de assets;
- organização de arquivos/coleções em certos fluxos;
- encaminhamento da tarefa para o modelo adequado.

REGRAS ATUAIS:
- o Agent é descrito como disponível na web/desktop;
- consultas textuais ao agente não consomem créditos, mas existe cota diária;
- a mídia que o agente gera consome créditos normalmente;
- resultados são salvos automaticamente no projeto aberto.

COMO PEDIR BEM AO AGENTE:
- declare o objetivo final;
- declare duração/formato;
- quebre o vídeo em tomadas curtas;
- forneça referências explícitas;
- diga o que deve permanecer consistente;
- diga o que pode variar;
- imponha restrições factuais, por exemplo “não invente UI”;
- peça variações controladas: “gere 4 versões mudando somente iluminação”.

Para projetos longos, use o agente como diretor de produção, não como um prompt gigante pedindo 90 segundos de uma vez. Peça plano → assets → takes → refinamentos → sequência.

**Fontes oficiais:**
- https://support.google.com/flow/answer/17093911?hl=en
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16935308?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=agent, workflow, variations, desktop

## 07. Anatomia de um prompt forte

A documentação oficial recomenda descrever assunto, ação, ambiente, iluminação e estilo. Na prática, prompts robustos podem ser modularizados assim:

1. SUBJECT / CHARACTER
Quem ou o que aparece. Se houver Character, use @Nome.

2. ACTION
Uma ação principal por take. Ações simples reduzem artefatos.

3. ENVIRONMENT
Local, época, clima, arquitetura, contexto.

4. OUTFIT / PROPS
Roupa, objetos e itens de cena. Não coloque atributos de identidade aqui se pretende variar roupa.

5. CAMERA
Enquadramento, lente aparente, posição, ângulo e movimento.

6. LIGHTING
Hora do dia, direção da luz, difusão, contraste.

7. MOTION
Ritmo do corpo, cabelo, tecido, câmera, fundo.

8. STYLE
Fotorealista, comercial premium, documental, UGC etc.

9. AUDIO / DIALOGUE
Som ambiente, SFX, música, fala exata e idioma.

10. CONTINUITY
O que deve ser idêntico entre takes.

11. CONSTRAINTS
O que não deve aparecer/mudar.

EXEMPLO-BASE:
@CharacterName
SCENE: modern kitchen, early morning.
ACTION: she prepares breakfast and photographs the plate.
CAMERA: medium shot, subtle handheld, slow push-in.
LIGHTING: soft natural window light.
STYLE: photorealistic premium lifestyle UGC.
AUDIO: quiet kitchen ambience.
CONTINUITY: preserve face, freckles, body proportions and voice.
CONSTRAINTS: no text, no fake app UI, no extra fingers, no logo generation.

Melhor um take bem definido de 4–10s do que várias ações complexas no mesmo prompt.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://blog.google/innovation-and-ai/products/flow-video-tips/
- https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/

**Metadados:** confiança=high; dinâmico=não; tags=prompting, camera, lighting, audio, continuity

## 08. Text to Video

Text to Video cria clipes diretamente de instruções textuais. É melhor para:
- establishing shots;
- cenas sem referência rígida;
- exploração visual;
- movimentos de câmera;
- B-roll;
- conceitos em que consistência entre takes ainda não é crítica.

Boas práticas:
- peça uma ação principal;
- especifique direção e intensidade do movimento;
- escreva o enquadramento explicitamente;
- descreva a luz;
- descreva ritmo/pacing;
- adicione áudio somente quando necessário;
- se o rosto/personagem precisa ser idêntico entre cenas, migre para Character/Ingredients/Frames.

Evite transformar um roteiro de 60–90 segundos em uma única geração. Use vários clipes e monte no Scenebuilder/editor.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=text-to-video, workflow, short-clips

## 09. Ingredients / referências visuais

Ingredients permitem reutilizar imagens de personagens, objetos, produtos e estilos como referências consistentes.

Uso recomendado:
- personagens recorrentes;
- produto físico;
- figurino específico;
- carro, embalagem, objeto hero;
- localização/estilo visual;
- elementos de marca sem depender de descrição textual.

A documentação recomenda referências limpas:
- fundo simples ou segmentado;
- sem objetos extras;
- aparência consistente entre referências;
- prompt textual complementar, não contraditório;
- referencie explicitamente o Ingredient no prompt.

Para produtos, prepare “packshots” limpos, idealmente frente/3/4/lateral.
Para personagens, referências de identidade devem priorizar rosto legível e corpo sem oclusões.

Evite referências visualmente incompatíveis entre si. Se as imagens sugerem estilos/idades/cores diferentes, o modelo precisa adivinhar e a consistência cai.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://blog.google/innovation-and-ai/products/flow-video-tips/

**Metadados:** confiança=high; dinâmico=não; tags=ingredients, references, consistency, products

## 10. Frames to Video

Frames to Video usa um frame inicial e, quando compatível, um frame final.

USOS:
- animar uma imagem existente;
- garantir composição inicial;
- transição A → B;
- preservar continuidade entre shots;
- forçar começo/fim de uma transformação;
- criar ponte visual entre storyboard frames.

RECEITA:
1. Crie/seleciona frame inicial aprovado.
2. Opcionalmente crie frame final.
3. Descreva somente o movimento/transição que deve acontecer entre eles.
4. Evite contradizer o conteúdo visual dos frames.
5. Se a identidade é crítica, use frames visualmente coerentes e, quando possível, Character/Ingredients junto.

Exemplo:
START: personagem parada diante da bancada.
END: personagem segurando o prato pronto.
PROMPT: "She calmly finishes plating the meal, moves naturally, then lifts the plate toward camera. Smooth realistic hand motion, fixed kitchen layout, soft morning light, no camera jump."

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/
- https://blog.google/innovation-and-ai/products/veo-updates-flow/

**Metadados:** confiança=high; dinâmico=não; tags=frames-to-video, start-frame, end-frame, transition

## 11. Characters reutilizáveis

Characters agrupam referências visuais e de áudio em uma entidade reutilizável.

FLUXO OFICIAL:
1. Abra Characters.
2. Crie novo personagem.
3. Descreva o personagem.
4. Faça upload ou gere 1–2 imagens visuais.
5. O personagem precisa de pelo menos uma imagem.
6. Dê um nome.
7. Selecione ou crie uma voz.
8. Opcionalmente adicione informações de personalidade/comportamento.
9. Use no prompt digitando @NomeDoPersonagem.

PRINCÍPIO MAIS IMPORTANTE:
O prompt de criação do Character deve definir IDENTIDADE, não prender cenário ou figurino, quando o objetivo é reutilização ampla.

FIXE:
- rosto;
- olhos;
- nariz;
- boca;
- sardas/marcas;
- tom de pele;
- cabelo base;
- idade aparente;
- proporções corporais;
- voz;
- traços comportamentais.

NÃO FIXE, se deseja variedade:
- academia;
- praia;
- uma roupa única;
- um objeto específico;
- uma pose;
- uma iluminação específica.

As referências ideais são limpas e complementares. Exemplo: close do rosto + corpo inteiro frontal.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=characters, identity, voice, consistency

## 12. Prompt mestre para personagem flexível

TEMPLATE:

Create a recurring photorealistic character based on the provided reference images.
Preserve the character's identity very closely and make them recognizable as the same person in every future scene.

CORE IDENTITY:
- [skin tone]
- [eyes]
- [hair color/texture]
- [face shape]
- [distinctive marks/freckles]
- [apparent age]
- [body proportions]
- realistic skin texture and natural imperfections

PERSONALITY:
- [confident / friendly / calm / charismatic / etc.]

CONSISTENCY RULES:
- preserve the same face
- preserve the same eye color
- preserve distinctive marks
- preserve apparent age
- preserve body proportions
- preserve overall identity

FLEXIBILITY:
Do not lock the character to a specific outfit, location, pose, background or activity.
Clothing, hairstyle styling, environment and activity may vary per scene while identity remains stable.

VISUAL QUALITY:
photorealistic, believable anatomy, natural skin, authentic human appearance.

AVOID:
plastic skin, beauty-filter look, doll-like features, identity drift, exaggerated anatomy, inconsistent age.

Para vídeos futuros:
@CharacterName + SCENE + OUTFIT + ACTION + CAMERA + LIGHTING + AUDIO + CONSTRAINTS.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=character-prompt, template, consistency

## 13. Vozes e diálogo

O Flow permite associar voz a Character e, em recursos compatíveis, criar voz personalizada a partir de uma voz base e uma descrição de performance.

Em prompts de diálogo:
- escreva a fala exata;
- declare idioma e variante, por exemplo Brazilian Portuguese;
- descreva ritmo, energia e intenção;
- evite pedir fala longa durante movimentos físicos complexos;
- para cenas de treino/ação, use voice-over sobre B-roll quando possível;
- mantenha a mesma voz em todos os takes de um personagem recorrente.

Exemplo:
VOICE: young adult Brazilian Portuguese, warm, conversational, medium pace, natural pauses, not a TV announcer.
DIALOGUE: "Uma foto do prato. E se ela fosse só o começo?"

Áudio em vídeo generativo pode falhar ou variar; a documentação oficial reconhece que a geração de áudio pode produzir resultados insuficientes e que falhas podem levar a reembolso de créditos.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16353333?hl=en
- https://blog.google/innovation-and-ai/products/veo-updates-flow/

**Metadados:** confiança=high; dinâmico=não; tags=audio, voice, dialogue, lip-sync

## 14. Avatars

Avatar é diferente de Character.

AVATAR:
- representação digital do próprio usuário;
- criada a partir de selfie/rosto e gravação de voz;
- pode ser chamada por @me;
- possui salvaguardas e restrições específicas;
- disponibilidade regional varia;
- dados de avatar não podem ser compartilhados por ferramentas públicas/projetos de certas formas.

CHARACTER:
- personagem reutilizável criada a partir de 1–2 imagens e descrição;
- pode ser pessoa fictícia ou design recorrente;
- nome próprio e voz opcional/personalizada.

Use Avatar quando o objetivo é a semelhança do próprio usuário; use Character para elenco recorrente de uma produção.

**Fontes oficiais:**
- https://support.google.com/labs/answer/17102997?hl=en
- https://support.google.com/flow/answer/16353544?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=avatar, character, likeness

## 15. Geração e edição de imagens

O Flow permite criar, editar e versionar imagens no mesmo projeto.

CAPACIDADES:
- gerar imagem por prompt;
- Agent roteia pedidos para o modelo adequado;
- editar imagem existente sem perder original;
- histórico de versões;
- crop;
- seleção/edição localizada;
- adicionar/remover objetos;
- criar frames e Ingredients;
- gerar várias variações de uma vez.

ESTRATÉGIA:
- use imagem como pré-produção;
- estabilize personagem/produto antes do vídeo;
- gere storyboard frames;
- faça correções de composição em imagem, que tendem a ser mais baratas e controláveis que refazer vídeo;
- então use Animate/Frames/Ingredients para vídeo.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/

**Metadados:** confiança=high; dinâmico=não; tags=image-editing, storyboard, preproduction

## 16. Edição de vídeo com Gemini Omni

O Flow suporta edição de vídeo enviado ou gerado, com Gemini Omni Flash em fluxos compatíveis.

DOCUMENTAÇÃO ATUAL:
- upload de vídeo de até 60 segundos e até 1 GB;
- formatos citados: .mov, .mp4, .avi, .wmv;
- se o vídeo enviado tiver mais de 30s, pode ser necessário cortá-lo;
- para edição, selecione um segmento de até 10s;
- descreva a alteração em linguagem natural;
- pode adicionar Ingredients;
- é possível continuar refinando por até três interações conversacionais mantendo o contexto da edição.

EXEMPLOS DE EDIÇÃO:
- trocar iluminação;
- alterar fundo;
- adicionar elemento;
- mudar estilo visual;
- aplicar texto/overlay quando o recurso/modelo permitir;
- criar variações mantendo o take base.

REGRA DE PRODUÇÃO:
Peça mudanças atômicas. “Mude somente a luz para pôr do sol, preserve personagem, câmera, ação e cenário” é mais previsível que mudar cinco dimensões de uma vez.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935718?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/

**Metadados:** confiança=high; dinâmico=não; tags=video-editing, omni, video-to-video

## 17. Extend / continuação de clipes

Extend cria filmagem adicional depois do final de um clipe compatível.

A documentação atual indica que a extensão é voltada a vídeos gerados pelo Veo e que o suporte varia por variante/modelo.

MELHOR USO:
- establishing shots;
- caminhada contínua;
- panorâmicas;
- cenas em que o final atual já aponta naturalmente para o próximo movimento.

A tecnologia usa o final do clipe como base para continuar. Portanto, o último segundo deve estar limpo e estável.

Evite tentar corrigir grandes erros por meio de Extend. Primeiro corrija o take, depois estenda.

Após extensão, alguns modos de edição avançada podem ficar indisponíveis para aquele clipe, conforme a documentação atual.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935718?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://blog.google/innovation-and-ai/products/veo-updates-flow/

**Metadados:** confiança=high; dinâmico=não; tags=extend, continuity, veo

## 18. Câmera e reshoot

Desde o lançamento, o Flow enfatiza controle de câmera. Atualizações posteriores adicionaram ajustes/refilmagem para mudar posição/movimento da câmera em material gerado.

VOCABULÁRIO ÚTIL:
- static tripod
- subtle handheld
- push-in / pull-back
- dolly in / dolly out
- pan left/right
- tilt up/down
- orbit
- tracking shot
- over-the-shoulder
- low angle / high angle
- close-up / medium / wide
- shallow depth of field
- 35mm / 50mm / 85mm look

BOA PRÁTICA:
Dê apenas um movimento principal por take. Um prompt pedindo dolly + orbit + zoom + pan costuma gerar movimento confuso.

Para UGC/influencer:
"subtle handheld micro movement" costuma ser mais natural que câmera perfeitamente robótica.

Para publicidade premium:
"slow cinematic push-in, stable subject framing, shallow depth of field".

Ajustes de câmera funcionam melhor em clipes que não já possuem movimento de câmera complexo.

**Fontes oficiais:**
- https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-refine-videos/

**Metadados:** confiança=high; dinâmico=não; tags=camera, reshoot, cinematography

## 19. Scenebuilder

Scenebuilder é a área para organizar clipes em sequência.

CAPACIDADES documentadas:
- adicionar clipes;
- reordenar;
- aparar início e fim;
- pré-visualizar sequência;
- baixar a cena montada.

Use Scenebuilder como montagem de rough cut, não como substituto total de um NLE profissional.

WORKFLOW:
1. Gere takes curtos.
2. Salve versões aprovadas.
3. Adicione ao Scenebuilder.
4. Ordene narrativa.
5. Ajuste trims.
6. Assista continuidade.
7. Gere/edite takes que quebram ritmo.
8. Exporte a sequência.
9. Faça acabamento externo se precisar de mixagem, motion graphics, legendas e UI precisa.

Para YouTube, a documentação indica que clipes individuais podem ter compartilhamento direto, enquanto sequência completa do Scenebuilder pode exigir download e upload posterior via YouTube Studio.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935718?hl=en
- https://support.google.com/flow/answer/16935308?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=scenebuilder, editing, sequence

## 20. Projetos, assets, coleções e histórico

O Flow organiza trabalho por projetos. Assets podem ser imagens, vídeos, frames e coleções.

RECURSOS:
- renomear projeto;
- excluir;
- download;
- modo grid/batch;
- coleções e coleções aninhadas;
- salvar versões anteriores;
- salvar frame de um vídeo como imagem;
- reutilizar frame salvo como Ingredient ou start/end frame;
- pesquisa visual/contextual em apps compatíveis;
- sincronização de projetos entre plataformas compatíveis.

PADRÃO DE ORGANIZAÇÃO RECOMENDADO:
Project/
  00_BRIEF
  01_CHARACTERS
  02_LOCATIONS
  03_PRODUCTS
  04_STORYBOARD
  05_GENERATIONS
  06_APPROVED_TAKES
  07_REJECTS
  08_SCENE_EXPORTS

NOMES:
S01_SH01_kitchen_intro_v03
S01_SH02_plate_photo_v05
S02_SH01_gym_wide_v02

Não confie apenas em miniaturas. Nomear assets economiza muito tempo em produções longas.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16935718?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=projects, assets, collections, history

## 21. Ferramentas customizadas / vibe coding

Em 2026 o Flow passou a permitir criação de ferramentas/miniapps reutilizáveis em linguagem natural.

FLUXO:
1. Abra Tools/Ferramentas.
2. Criar ferramenta.
3. Descreva a ferramenta.
4. O Flow gera código/interface.
5. Revise e salve.
6. Ferramentas podem ser editadas por instruções de linguagem natural.
7. Algumas podem ser compartilhadas/remixadas.

EXEMPLOS:
- resizer de vídeo;
- overlays;
- image editor;
- filtros/shaders;
- mockups;
- pipelines repetitivos de transformação.

REGRA:
Use ferramenta customizada quando a tarefa se repete. Não gaste energia com um prompt manual idêntico em dezenas de assets.

A mídia produzida por Tools pode consumir créditos. A criação/consulta do agente possui cotas próprias.

**Fontes oficiais:**
- https://support.google.com/flow/answer/17104535?hl=en
- https://labs.google/fx/tools/flow
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates/

**Metadados:** confiança=high; dinâmico=não; tags=tools, vibe-coding, automation

## 22. Workflow profissional de personagem consistente

FASE A — Character Bible
Defina:
- nome;
- idade aparente;
- rosto;
- olhos;
- cabelo;
- pele;
- marcas/sardas;
- proporções;
- personalidade;
- voz;
- limites de variação.

FASE B — referências
Escolha 1–2 imagens:
- close limpo do rosto;
- corpo inteiro;
- mesma identidade;
- luz neutra;
- sem objetos cobrindo face/corpo.

FASE C — crie o Character
Faça upload das imagens, dê nome, voz e informações comportamentais.

FASE D — teste de consistência
Gere 4–6 takes curtos:
- cozinha;
- rua;
- academia;
- exterior;
- close;
- corpo inteiro.
Mude roupas e locais, não identidade.

FASE E — lock
Escolha um prompt mestre e não reescreva características de identidade contraditórias em cada take.

FASE F — continuidade
Use @Character + Frames/Ingredients quando a cena exigir continuidade forte.

SINAIS DE IDENTITY DRIFT:
- formato do nariz muda;
- cor dos olhos muda;
- sardas desaparecem;
- idade oscila;
- corpo muda de proporção;
- cabelo muda radicalmente sem instrução.

CORREÇÃO:
- reduza instruções;
- reforce 2–4 traços distintivos;
- use referência mais limpa;
- gere frame estático primeiro;
- transforme o frame aprovado em vídeo.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=character-consistency, workflow, identity-drift

## 23. Workflow para anúncio vertical / influencer

OBJETIVO: vídeo 9:16 para Reels/TikTok com personagem recorrente e produto/app.

1. ROTEIRO
Divida em hooks, demonstração, prova visual e CTA.

2. TAKES
Faça clipes de 4–10 segundos; uma ação por take.

3. PERSONAGEM
Use Character recorrente. Roupa e cenário podem variar.

4. UI REAL
Se anunciar software/app:
- grave a interface real;
- na geração, use celular com tela neutra;
- insira screen recording na edição;
- não invente números, telas, comentários ou funções.

5. FALA
Falas diretas curtas. Em ações físicas, prefira voice-over.

6. B-ROLL
Mãos, prato, celular, treino, detalhes, caminhada, reação.

7. CÂMERA
Misture medium, close, insert shots e tracking leve.

8. IDENTIDADE
Preserve rosto/voz. Deixe figurino variar com a cena.

9. MARCA
Logos e textos exatos devem ser aplicados em edição quando precisão tipográfica importa.

10. FINALIZAÇÃO
Legendas fiéis, áudio licenciado, revisão de mãos/rosto/objetos, continuidade e fatos.

Essa abordagem reduz hallucination visual e deixa o gerador focar no que faz melhor: pessoas, cena, luz, movimento e atmosfera.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16935718?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=advertising, ugc, vertical-video, software-demo

## 24. Template de prompt para Agent produzir uma sequência

Use este template no Agent:

GOAL:
Create a [duration] [aspect ratio] production for [purpose].

CHARACTER:
Use @CharacterName in every scene.
Preserve face, eyes, distinctive marks, apparent age, body proportions and voice.
Clothing and location may change.

GLOBAL STYLE:
[photorealistic / premium commercial / UGC / documentary].

PRODUCTION METHOD:
Break the video into separate 4–10 second shots.
One primary action per shot.
Generate multiple controlled variants when useful.
Do not attempt the entire long video as a single generation.

SCENE 01:
LOCATION:
OUTFIT:
ACTION:
DIALOGUE:
CAMERA:
LIGHTING:
AUDIO:
CONSTRAINTS:

SCENE 02:
...

CONTINUITY:
List what must remain identical.

FACTUAL RESTRICTIONS:
Do not invent interfaces, product claims, logos, metrics or user data.

DELIVERABLE:
Create and organize the required shots in narrative order. Keep alternates separated from approved takes.

Para comercial de app, acrescente:
"When a phone screen is visible, keep it neutral and suitable for compositing real screen recordings later."

**Fontes oficiais:**
- https://support.google.com/flow/answer/17093911?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=agent-prompt, template, sequence, ads

## 25. Template de Frames to Video

@CharacterName

INPUTS:
- Start frame: [describe/refer to attached frame]
- End frame: [describe/refer to attached frame]

TRANSITION:
Describe only the physical action that connects the two frames.

CAMERA:
Keep camera [static / slow push-in / tracking].

MOTION:
Natural body mechanics, realistic hands, consistent hair and clothing motion.

LIGHT:
Preserve lighting continuity between frames.

IDENTITY:
Preserve character identity exactly.

CONSTRAINTS:
No cuts, no teleporting, no new objects, no face drift, no text.

Exemplo:
"She calmly raises the cup from the counter, takes one natural sip and lowers it while maintaining eye contact with the camera. Fixed kitchen layout. Subtle handheld micro-movement. Preserve face and freckles. No scene transition."

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=frames-prompt, template

## 26. Template de edição video-to-video

EDIT REQUEST:
Change ONLY: [one target change].

PRESERVE:
- subject identity;
- facial features;
- body proportions;
- action timing;
- camera position/motion;
- original objects;
- composition;
- audio/dialogue, unless explicitly changed.

TARGET:
[precise requested change]

EXAMPLE:
"Change only the lighting to warm golden-hour sunlight entering from camera-left. Preserve the woman's face, hair, clothing, body, motion, camera path, gym equipment and timing. Do not add or remove objects."

Quando precisar de uma segunda alteração, faça outra iteração em vez de acumular tudo no primeiro pedido.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935718?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/

**Metadados:** confiança=high; dinâmico=não; tags=video-edit-prompt, template, atomic-edits

## 27. Prompt de produto consistente

Use Ingredients limpos para produto.

TEMPLATE:
Use @ProductReference as the exact product reference.

Preserve:
- packaging geometry;
- colors;
- cap shape;
- proportions;
- material;
- label placement.

SCENE:
[environment]

ACTION:
[interaction]

CAMERA:
[shot]

LIGHTING:
[light]

STYLE:
[premium product commercial / lifestyle]

CONSTRAINTS:
Do not redesign packaging.
Do not invent extra text.
Do not change logo.
Do not alter product proportions.

Para logos e textos legalmente/visualmente críticos, a estratégia mais segura é compor a marca final em edição.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://blog.google/innovation-and-ai/products/flow-video-tips/

**Metadados:** confiança=high; dinâmico=não; tags=product, ingredients, branding

## 28. Troubleshooting: personagem inconsistente

PROBLEMA: o rosto muda entre cenas.
AÇÕES:
- use Character, não apenas descrição textual;
- use 1–2 referências limpas;
- evite misturar referências que parecem pessoas diferentes;
- reduza mudanças simultâneas;
- reforce traços distintivos;
- estabilize uma imagem antes de animar;
- use frame aprovado como começo do vídeo.

PROBLEMA: roupa fica presa ao personagem.
AÇÕES:
- remova roupa do prompt mestre da identidade;
- deixe roupa explicitamente em OUTFIT por cena;
- se imagens de referência mostram sempre a mesma roupa, gere referências neutras quando necessário.

PROBLEMA: corpo muda.
AÇÕES:
- inclua corpo inteiro em uma referência;
- descreva proporções de forma natural e breve;
- não use prompts conflitantes de corpo por cena.

PROBLEMA: personagem parece artificial.
AÇÕES:
- peça natural skin texture, pores, subtle imperfections;
- remova “perfect”, “flawless”, “beauty filter”;
- use luz natural e câmera menos polida.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=troubleshooting, character, identity

## 29. Troubleshooting: mãos, celular, objetos e UI

MÃOS:
- reduza ações simultâneas;
- evite manipulação minuciosa em plano aberto;
- use inserts/close-ups próprios;
- regenere apenas o take problemático.

CELULAR:
- mantenha modelo/forma genéricos e consistentes;
- peça screen neutral/blank para composição;
- não dependa do gerador para UI real.

OBJETOS:
- use Ingredients;
- referências limpas;
- uma ação física por take.

TEXTOS/LOGOS:
- modelos de imagem melhoraram muito em typography, mas para marca oficial, preços, claims e UI, prefira pós-produção.

INTERFACE:
- screen recording real > interface generativa;
- valide o recurso real antes de anunciar.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16352836?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=troubleshooting, hands, phone, ui, branding

## 30. Troubleshooting: áudio e lip sync

Se o áudio falhar:
- tente nova geração;
- simplifique fala;
- reduza ruído/efeitos simultâneos;
- se necessário, gere take sem fala e faça voz externa;
- a documentação informa que falhas de áudio podem resultar em geração não entregue/reembolso de créditos.

Para lip sync:
- frases curtas;
- close ou medium close;
- pouco movimento corporal;
- não faça personagem virar de costas durante fala importante;
- evite fala durante exercício intenso;
- preserve a mesma voz entre takes.

Para anúncio natural:
"conversational, warm, medium pace, natural pauses, not a commercial announcer."

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353333?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=troubleshooting, audio, lip-sync

## 31. Privacidade e dados

O Google informa que coleta interações, outputs, uso relacionado e feedback para fornecer, melhorar e desenvolver produtos/tecnologias, sujeito às configurações e ao aviso de privacidade do Flow.

Existe uma configuração equivalente a “Help improve Google Flow”. Quando habilitada, uploads, interações, resultados e feedback podem ser usados para melhoria, conforme o aviso aplicável.

A orientação oficial é não inserir informações confidenciais que o usuário não gostaria que fossem revisadas/usadas conforme a política.

Há controles para:
- excluir projetos;
- excluir todos os projetos;
- gerenciar dados do Agent/Tools;
- desativar participação em melhoria do produto em configurações compatíveis.

Para produção com clientes:
- não suba dados sensíveis sem autorização;
- remova PII desnecessária;
- use contas/demo data para interfaces;
- revise o aviso de privacidade atual antes de workflows corporativos.

**Fontes oficiais:**
- https://support.google.com/flow/answer/17025472?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=privacy, data, enterprise

## 32. SynthID, marca d'água e proveniência

Outputs gerados com modelos do Flow incluem marca d'água invisível SynthID, conforme documentação atual.

A documentação também descreve opção de watermark visível em certos contextos/regiões. Em alguns países a marca visível pode ser aplicada automaticamente.

SynthID serve para indicar conteúdo gerado por IA e não deve ser adulterado/removido.

Para publicação profissional:
- mantenha metadados/proveniência quando aplicável;
- cumpra regras da plataforma de destino sobre conteúdo sintético;
- se o conteúdo retrata pessoa virtual, considere disclosure apropriado;
- não apresente personagem sintético como testemunho factual de experiência que nunca ocorreu.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353333?hl=en
- https://support.google.com/flow/answer/16935308?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=synthid, watermark, provenance

## 33. Uso comercial e direitos

O Help Center remete aos Termos de Serviço para uso dos outputs. A formulação oficial indica que o Google não reivindica propriedade sobre conteúdo original gerado quando os Termos aplicáveis permitem geração de conteúdo.

NÃO interprete isso como garantia universal de que qualquer output é comercialmente seguro.

Antes de uso comercial:
- confirme Termos atuais;
- garanta direitos sobre uploads e referências;
- não use marcas, personagens ou likeness de terceiros sem autorização;
- verifique música/licenças;
- revise claims publicitários;
- respeite direitos de imagem;
- evite usar geração para falsificar prova, depoimento, resultado ou interface.

Quando a pergunta for jurídica, não substitua aconselhamento profissional por este resumo.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353333?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=commercial-use, rights, terms

## 34. Restrições e segurança relevantes

A disponibilidade e permissões variam por região. A documentação de disponibilidade cita restrições específicas, incluindo:
- edição de vídeos enviados de menores identificáveis não é suportada;
- geração de vídeos de pessoas famosas possui restrições;
- edição de vídeo enviado e Avatars podem estar indisponíveis em determinadas regiões como EEE, Suíça e Reino Unido.

O Flow aplica políticas de uso de IA generativa e pode bloquear pedidos.

Ao diagnosticar bloqueios:
- não presuma bug imediatamente;
- verifique política;
- verifique região;
- verifique modelo;
- verifique tipo de mídia;
- verifique VPN/proxy;
- tente simplificar o prompt sem contornar salvaguardas.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16353544?hl=en
- https://support.google.com/flow/answer/16353333?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=safety, policy, regional-restrictions

## 35. Histórico de evolução do produto

2025-05:
- lançamento do Flow como ferramenta de filmmaking;
- Veo, Imagen e Gemini;
- Camera Controls, Scenebuilder, asset management;
- Veo 3 com áudio nativo.

2025-06/07:
- documentação pública de boas práticas;
- Ingredients e Frames ganham destaque;
- expansão regional;
- speech/áudio em fluxos compatíveis.

2025-10:
- Veo 3.1;
- áudio mais rico em Ingredients, Frames e Extend;
- maior controle narrativo;
- Insert/Remove em evolução.

2025-11:
- Nano Banana Pro e mais edição/refino;
- doodle prompting;
- insert/remove;
- camera adjustment/reshoot.

2026-02:
- redesign do Flow;
- imagem passa a ser parte central do workspace;
- convergência de capacidades de experimentos de imagem no Flow;
- asset management e editing refinados.

2026-05:
- Gemini Omni;
- novos agentes;
- mobile apps;
- Flow Tools/vibe coding;
- Flow evolui de filmmaking tool para creative studio.

2026-08:
- Gemini Omni 1.1 Flash;
- mais controle com start/end frames;
- draft 360p;
- upscale e export de maior resolução;
- foco em workflows production-ready.

IMPORTANTE: tutoriais de 2025 podem mencionar Veo 2/Veo 3 e limitações que já mudaram. Sempre classifique material antigo como histórico.

**Fontes oficiais:**
- https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/
- https://blog.google/innovation-and-ai/products/flow-video-tips/
- https://blog.google/innovation-and-ai/products/veo-updates-flow/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-refine-videos/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates/
- https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/

**Metadados:** confiança=high; dinâmico=não; tags=history, updates, timeline

## 36. Diferenças entre Flow e produtos relacionados

GOOGLE FLOW
Estúdio criativo visual/audiovisual. Projetos, vídeo, imagem, Agent, Characters, Avatars, Tools, Scenebuilder.

GEMINI APP
Assistente geral. Pode gerar mídia em determinados planos/modelos, mas não substitui o workspace de produção e asset management do Flow.

VERTEX AI / GEMINI API
Acesso programático/enterprise a modelos. Adequado para pipelines de software e integração, não é a mesma interface criativa do Flow.

GOOGLE FLOW MUSIC
Produto relacionado dedicado a música e criação musical, com agentes/modelos próprios.

GOOGLE WORKSPACE STUDIO / WORKSPACE FLOWS
Automação de processos de trabalho. Não confundir com o Flow de mídia.

FLOW TV
Galeria/showcase de conteúdo criado com Veo/Flow para inspiração.

**Fontes oficiais:**
- https://labs.google/fx/tools/flow
- https://support.google.com/flow/answer/16353333?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates/

**Metadados:** confiança=high; dinâmico=não; tags=related-products, gemini, vertex, flow-music, workspace

## 37. Estratégia de economia de créditos

1. Faça storyboard em imagem antes do vídeo.
2. Teste composição/movimento em resolução draft quando disponível.
3. Use takes curtos.
4. Gere poucas variáveis por vez.
5. Reutilize frames aprovados.
6. Edite take aprovado em vez de regenerar do zero quando a edição é compatível.
7. Evite pedir 5 resultados quando 2 bastam.
8. Reserve Quality/4K para finais.
9. Use Agent para planejar, mas lembre que a mídia gerada consome créditos.
10. Confira o custo na UI antes de confirmar geração.

A otimização real não é “usar sempre o modelo mais barato”; é reduzir gerações desperdiçadas.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16526234?hl=en
- https://support.google.com/flow/answer/16352836?hl=en
- https://support.google.com/flow/answer/17093911?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=credits, optimization, workflow

## 38. Checklist antes de gerar

- O objetivo do take está claro?
- Existe apenas uma ação principal?
- Character/Ingredient certo foi anexado?
- Frame inicial/final realmente combina com o prompt?
- O modelo escolhido suporta o recurso?
- A duração é suficiente?
- Proporção correta?
- Custo de créditos confirmado?
- Roupa e cenário estão separados da identidade?
- Câmera tem um movimento principal?
- Fala é curta e clara?
- Precisa de áudio ou pode ser voice-over?
- Há texto/logo/UI que deve ser feito em pós?
- O prompt contradiz a referência?
- Alguma informação sensível foi anexada?

**Fontes oficiais:**
- https://support.google.com/flow/answer/16352836?hl=en
- https://support.google.com/flow/answer/16526234?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=checklist, generation

## 39. Checklist de QA do take

ROSTO:
- identidade correta;
- olhos;
- nariz;
- sardas/marcas;
- idade.

CORPO:
- proporções;
- anatomia;
- mãos;
- pés.

OBJETOS:
- celular;
- embalagem;
- continuidade;
- escala e contato físico.

CÂMERA:
- movimento pretendido;
- sem saltos;
- framing.

ÁUDIO:
- voz correta;
- lip sync;
- ruído;
- pronúncia;
- fala completa.

CENA:
- luz;
- cenário;
- objetos extras;
- texto acidental.

MARCA/FATOS:
- não há logo inventado;
- não há UI falsa;
- não há claim incorreto;
- não há resultado corporal encenado como prova.

Se um erro é localizado, edite/regere somente o take afetado.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935718?hl=en
- https://support.google.com/flow/answer/16353334?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=qa, quality-control, production

## 40. Regras para responder a futuros pedidos sobre Flow

Quando o usuário pedir “me dê o prompt”:
1. Identifique se é Text to Video, Frames, Ingredients, Character, Agent ou Edit.
2. Escolha o template correto.
3. Preserve referências que o usuário já forneceu.
4. Não repita descrição física inteira se @Character já resolve identidade, salvo para corrigir drift.
5. Separe diálogo em campo próprio.
6. Coloque câmera e iluminação explicitamente.
7. Acrescente continuity e constraints.
8. Se for projeto longo, produza cena a cena.
9. Se houver UI/logomarca exata, recomende composição real na edição.
10. Se a função/modelo for dinâmica, verifique documentação atual antes de afirmar compatibilidade.

Quando o usuário disser “ficou diferente”:
- diagnostique uma dimensão de cada vez;
- não reescreva tudo sem necessidade;
- use edição iterativa ou frame aprovado.

Quando o usuário pedir “faça um personagem”:
- 1–2 referências;
- close + full body;
- identidade fixa;
- ambiente/roupa fora do prompt mestre quando devem variar;
- voz/personality no perfil.

**Fontes oficiais:**
- https://support.google.com/flow/answer/16935308?hl=en
- https://support.google.com/flow/answer/17093911?hl=en
- https://support.google.com/flow/answer/16353334?hl=en
- https://support.google.com/flow/answer/16935718?hl=en

**Metadados:** confiança=high; dinâmico=não; tags=future-answers, codex, prompt-generation

## 41. Índice de fontes oficiais

- `flow_home`: https://labs.google/fx/tools/flow
- `get_started`: https://support.google.com/flow/answer/16353333?hl=en
- `create_video`: https://support.google.com/flow/answer/16353334?hl=en
- `models`: https://support.google.com/flow/answer/16352836?hl=en
- `credits`: https://support.google.com/flow/answer/16526234?hl=en
- `projects_characters`: https://support.google.com/flow/answer/16935308?hl=en
- `edit_video`: https://support.google.com/flow/answer/16935718?hl=en
- `agent`: https://support.google.com/flow/answer/17093911?hl=en
- `tools`: https://support.google.com/flow/answer/17104535?hl=en
- `data`: https://support.google.com/flow/answer/17025472?hl=en
- `availability`: https://support.google.com/flow/answer/16353544?hl=en
- `avatar`: https://support.google.com/labs/answer/17102997?hl=en
- `launch`: https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/
- `tips_2025`: https://blog.google/innovation-and-ai/products/flow-video-tips/
- `veo31_2025`: https://blog.google/innovation-and-ai/products/veo-updates-flow/
- `refine_2025`: https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-refine-videos/
- `feb_2026`: https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates-february-2026/
- `may_2026`: https://blog.google/innovation-and-ai/models-and-research/google-labs/flow-updates/
- `aug_2026`: https://blog.google/innovation-and-ai/models-and-research/google-labs/new-creative-controls-google-flow/
