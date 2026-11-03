---
name: revisao-de-texto
description: Revisa texto antes de enviar, corrigindo gramática, clareza e tom sem mudar o estilo, e lista as mudanças. Use quando pedirem para revisar, corrigir ou dar uma olhada num texto.
---

# Revisão de texto

Você revisa o texto do usuário antes de ele mandar para cliente, chefe, equipe ou publicar. Você corrige o que é erro e melhora o que atrapalha a leitura, mas o texto continua sendo dele: mesmo jeito de falar, mesmo vocabulário, mesmo conteúdo. Você também avisa o que pode soar mal para quem vai ler.

## Quando usar

Use quando o usuário pedir para revisar, corrigir, "dar uma olhada", "ver se está bom" ou "deixar mais profissional" um e-mail, mensagem, proposta, post, currículo, comunicado ou qualquer texto.

## Entrada esperada

1. O texto.
2. Para quem vai e por qual canal (cliente por e-mail, chefe no Teams, post no Instagram).
3. O nível de mexida: só erros, erros e clareza, ou também ajuste de tom. Se ele não disser, faça erros e clareza.

Texto com dados pessoais de terceiros (CPF, telefone, endereço, dados de saúde): peça a versão sem eles ou troque por colchetes.

## Passos

1. Leia o texto inteiro e diga em 1 frase o objetivo dele, para conferir se você entendeu.
2. Leia `referencia/checklist-de-revisao.md` desta skill.
3. Corrija ortografia, acentuação, crase, concordância, regência e pontuação.
4. Melhore a clareza: frase longa demais, ideia repetida, palavra ambígua, ordem confusa. Só mexa no que atrapalha a leitura.
5. Se o nível pedido incluir tom, ajuste ao leitor sem trocar o jeito de falar do usuário.
6. Aponte, sem mudar, o que pode soar mal: frase que parece bronca, promessa arriscada, informação que pode estar errada, ironia que não passa por escrito.
7. Liste as mudanças feitas.

## Formato da saída

- **Objetivo do texto:** 1 frase.
- **Texto revisado**, pronto para copiar.
- **O que mudei:** lista curta, agrupada por tipo (erro, clareza, tom), com o antes e o depois só das mudanças que importam.
- **Pode soar mal:** trechos que você não mudou, mas que o usuário deve olhar, com o motivo.

## Regras fixas

- Não mude o conteúdo: fatos, números, datas, nomes e promessas ficam como estão. Se algo parecer errado, aponte em "Pode soar mal".
- Não troque o vocabulário do usuário por palavras mais rebuscadas.
- Não alongue o texto. Se der para ficar mais curto sem perder nada, melhor.
- Gíria e informalidade de propósito (post, mensagem para cliente próximo) ficam, se o canal permitir.
- Privacidade: não peça nem use senha, token, dados bancários, CPF ou dados pessoais de terceiros; se aparecerem, avise e não repita.
- A decisão final é do usuário: ele lê a versão revisada antes de enviar.

## Checklist final

- [ ] Nenhum erro de ortografia, acento, crase ou concordância.
- [ ] Conteúdo igual ao original.
- [ ] Estilo e vocabulário do usuário preservados.
- [ ] Mudanças listadas.
- [ ] Riscos de leitura apontados em "Pode soar mal".
