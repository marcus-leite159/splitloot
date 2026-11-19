# Split Loot

Calculadora de divisão de loot (profit split) para party hunts no Tibia. Cole o texto do **Party Hunt Analyzer**, ajuste o que precisar e copie os comandos de transferência do banco prontos.

**Acesse:** https://SEU-USUARIO.github.io/split-loot/

## Como usar

1. No Tibia, abra o **Party Hunt Analyzer** e clique em **Copy to clipboard**.
2. Cole o texto no Split Loot e clique em **Calcular split** (ou Ctrl+Enter).
3. Ajuste se precisar:
   - edite o **loot** ou os **supplies** de qualquer membro direto no card;
   - some **gastos extras** (SD, imbuements, pots) a um jogador;
   - **remova** ou **adicione** membros manualmente.
4. Copie os comandos:
   - **Copiar**, em cada linha, copia só o comando para colar no NPC do banco;
   - **Copiar bloco** copia o título e as transferências de um pagador;
   - **Copiar resumo para o Discord** copia tudo formatado, com o nome de cada pagador em negrito.

Os valores aceitam `150k`, `1,5kk`, `1.500.000` ou `1,500,000`.

## Como o cálculo funciona

- Saldo de cada jogador = loot − (supplies + gastos extras).
- Parte por jogador = saldo total ÷ número de membros.
- Quem ficou acima da parte paga a diferença a quem ficou abaixo. Os maiores pagadores são combinados com os maiores recebedores, para gerar o menor número de transferências.
- Sobras de até 1 gp por jogador ficam com quem paga, por arredondamento.

## Uso offline

É um único arquivo HTML, sem instalação e sem servidor. Baixe o `index.html` e abra no navegador. Sem internet, só a fonte muda para a do sistema; o resto funciona igual. Nenhum dado sai do seu computador.

## Publicar no GitHub Pages

1. Crie um repositório público (ex.: `split-loot`) e envie o `index.html` e este `README.md`.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em um ou dois minutos o site fica em `https://SEU-USUARIO.github.io/split-loot/`.
4. Troque `SEU-USUARIO` no link do topo deste README.

## Aviso

Projeto de fã, sem vínculo com a CipSoft GmbH. Tibia é marca registrada da CipSoft.
