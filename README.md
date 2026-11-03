# Skill Revisão de texto para o Claude

Corrige gramática, clareza e tom do seu texto sem mudar o seu jeito de escrever, e lista cada mudança que fez. Serve para e-mail, mensagem para cliente, proposta, post e qualquer texto antes de enviar.

Presente das lives diárias das 14h da Overclock: [overclock.sh/lives](https://overclock.sh/lives).

## Como instalar no claude.ai ou no app do Claude

1. Em **Settings > Capabilities**, ligue **Code execution and file creation**. As skills dependem dele.
2. Baixe o arquivo **revisao-de-texto.zip** na página de [Releases](../../releases/latest) e não descompacte.
3. Abra **Customize > Skills**, envie o ZIP e deixe a skill ligada.
4. Numa conversa nova, peça: "Revisa este e-mail antes de eu mandar para o cliente."

## Como instalar no Claude Code

```bash
git clone https://github.com/ustoppble/skill-revisao-de-texto ~/.claude/skills/revisao-de-texto
```

Abra o Claude Code de novo e peça a revisão do jeito de sempre.

## O que tem aqui

- `SKILL.md`: as instruções da skill.
- `referencia/checklist-de-revisao.md`: o checklist que a skill segue em cada revisão.

## Cuidado

Não cole na conversa senhas, chaves, dados bancários nem dados pessoais de clientes. A decisão final é sua: leia a versão revisada antes de enviar.

Claude é marca da Anthropic. A Overclock não tem vínculo com a Anthropic.
