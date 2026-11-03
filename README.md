# Skill Revisão de texto para o Claude

Corrige gramática, clareza e tom do seu texto sem mudar o seu jeito de escrever, e lista cada mudança que fez. Serve para e-mail, mensagem para cliente, proposta, post e qualquer texto antes de enviar.

Presente das lives diárias das 14h da Overclock: [overclock.sh/lives](https://overclock.sh/lives).

## Como instalar no claude.ai ou no app do Claude

Vale para os planos Free, Pro, Max, Team e Enterprise.

1. Em **Settings > Capabilities**, ligue **Code execution and file creation**. As skills dependem dele.
2. Baixe o arquivo [revisao-de-texto.zip](https://github.com/ustoppble/skill-revisao-de-texto/releases/latest/download/revisao-de-texto.zip) e não descompacte.
3. Abra **Customize > Skills**, toque no **+**, depois em **+ Create skill** e em **Upload a skill**.
4. Envie o ZIP. A skill aparece na lista; deixe ela ligada.
5. Numa conversa nova, peça: "Revisa este e-mail antes de eu mandar para o cliente."

Use o ZIP do link acima, e não o botão **Code > Download ZIP** do GitHub: o do GitHub vem dentro de uma pasta com o nome do repositório, e o upload do Claude exige que a pasta tenha o mesmo nome da skill (`revisao-de-texto`).

## Como instalar no Claude Code

```bash
git clone https://github.com/ustoppble/skill-revisao-de-texto ~/.claude/skills/revisao-de-texto
```

O Claude Code pega a skill na sessão aberta, sem reiniciar. Se a pasta `~/.claude/skills` ainda não existia quando você abriu o Claude Code, rode `/reload-skills`. Depois é só pedir a revisão do jeito de sempre.

## O que tem aqui

- `SKILL.md`: as instruções da skill.
- `referencia/checklist-de-revisao.md`: o checklist que a skill segue em cada revisão.

## Cuidado

Não cole na conversa senhas, chaves, dados bancários nem dados pessoais de clientes. A decisão final é sua: leia a versão revisada antes de enviar.

Claude é marca da Anthropic. A Overclock não tem vínculo com a Anthropic.
