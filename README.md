# Fluxo Ágil® — Idea to Spec

**Organize uma ideia antes de começar a construir com IA.**

Skill gratuita e introdutória para Claude Code. Ela conduz uma conversa breve e transforma uma ideia inicial em um **briefing de projeto para revisão**: problema, público, objetivo, funcionalidades prioritárias, limites e dúvidas pendentes.

## O que entrega
- Perguntas de esclarecimento, em rodadas curtas.
- Síntese do problema, do usuário e do resultado desejado.
- Até três funcionalidades prioritárias para uma primeira versão.
- Restrições, hipóteses e pontos que ainda precisam ser decididos.
- Briefing inicial em Markdown, apresentado na conversa.

**Não entrega** PRD técnico completo, arquitetura, requisitos detalhados, critérios formais de aceite, plano de implementação, testes ou publicação. Não programa nem altera arquivos sem autorização.

## Instalação no Claude Code

1. Baixe este repositório como ZIP e extraia os arquivos.
2. No projeto em que usa Claude Code, crie a pasta `.claude/skills/idea-to-spec/`.
3. Copie para ela o arquivo `skills/idea-to-spec/SKILL.md` e a pasta `skills/idea-to-spec/examples/`.
4. Abra o Claude Code no projeto e peça: `Use a skill idea-to-spec para organizar minha ideia em um briefing inicial. Não programe nem altere arquivos.`

A disponibilidade e descoberta de Skills dependem da versão e da configuração do Claude Code. Confira se ela foi reconhecida no seu ambiente.

## Exemplo

> Quero organizar meus contatos comerciais e lembrar dos próximos retornos. Use a Skill Idea to Spec para preparar um briefing inicial, sem desenvolver o sistema.

Consulte o [exemplo fictício](skills/idea-to-spec/examples/mini-crm.md).

## Escopo e autoria

Esta é uma ferramenta introdutória independente, criada por **Eduardo Ponce (Du Ponce)**, do **Fluxo Ágil®**. Não representa nem substitui os materiais, exercícios, protocolos e acompanhamento das formações oficiais.

## Estado

**1.0.1 — Edição pública introdutória.** Esta edição simplificada requer validação específica de instalação e comportamento no Claude Code; a validação da edição anterior não substitui esse teste.

## Condições de uso

© 2026 Eduardo Ponce — Fluxo Ágil®. Todos os direitos reservados.

Uso gratuito em projetos pessoais, educacionais e profissionais. Redistribuição, comercialização, publicação de versões modificadas ou uso da marca Fluxo Ágil® em produtos de terceiros dependem de autorização prévia do titular. Estas condições são termos próprios de uso, não uma licença open source padronizada.

## Segurança

Não informe tokens, senhas, chaves de API ou dados pessoais sensíveis durante a entrevista. Use dados fictícios em exemplos públicos.
