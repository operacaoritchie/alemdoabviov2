---
name: Além do Óbvio
description: Página de venda da imersão presencial de Full Face com o Dr. Ritchie, em preto, osso e ouro velho.
colors:
  preto-sala: "#050505"
  superficie-camara: "#0F0E0C"
  rolo-filme: "#070605"
  barra-noturna: "#0E0D0A"
  miolo-escuro: "#0C0A07"
  osso: "#EDE6D8"
  cinza-pergaminho: "#A39A8B"
  tinta-osso: "#17130E"
  texto-sobre-ouro: "#15110A"
  ouro-velho: "#C9A35A"
  ouro-claro: "#D9BC7C"
  ouro-fundo: "#B8924A"
  ouro-escuro: "#9C7A3C"
  linha-fina: "rgba(237,230,216,.14)"
  erro-coral: "#E29A86"
typography:
  display:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(46px,5.6vw,96px)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(40px,6.2vw,96px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(28px,2.6vw,40px)"
    fontWeight: 400
    lineHeight: 1.1
  eyebrow:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(17px,1.35vw,20px)"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Manrope, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Manrope, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "13.5px"
    fontWeight: 500
    lineHeight: 1.5
  mono:
    fontFamily: "IBM Plex Mono, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "11px"
    fontWeight: 400
    letterSpacing: "0.2em"
rounded:
  none: "0"
  pill: "999px"
  circle: "50%"
spacing:
  margem: "clamp(20px,4.4vw,72px)"
  cena: "140px"
  vao-colunas: "clamp(40px,7vw,120px)"
  item: "34px"
  campo: "20px"
components:
  button-primary:
    backgroundColor: "{colors.ouro-velho}"
    textColor: "{colors.texto-sobre-ouro}"
    rounded: "{rounded.pill}"
    padding: "8px 8px 8px 28px"
    height: "60px"
  button-ghost:
    backgroundColor: "rgba(5,5,5,.35)"
    textColor: "{colors.osso}"
    rounded: "{rounded.pill}"
    padding: "11px 22px"
  button-ghost-hover:
    textColor: "{colors.ouro-velho}"
  barra-fixa:
    backgroundColor: "{colors.barra-noturna}"
    textColor: "{colors.osso}"
    rounded: "{rounded.pill}"
    padding: "7px 7px 7px 24px"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.osso}"
    rounded: "{rounded.pill}"
    padding: "9px 17px"
  chip-selected:
    backgroundColor: "rgba(201,163,90,.14)"
    textColor: "{colors.ouro-velho}"
    rounded: "{rounded.pill}"
  input-linha:
    backgroundColor: "transparent"
    textColor: "{colors.osso}"
    rounded: "{rounded.none}"
    padding: "8px 0 12px"
  marca-checklist:
    backgroundColor: "transparent"
    rounded: "{rounded.circle}"
    size: "22px"
  dialog-formulario:
    backgroundColor: "{colors.superficie-camara}"
    textColor: "{colors.osso}"
    rounded: "{rounded.none}"
    padding: "clamp(24px,5vw,48px)"
    width: "min(640px, calc(100% - 24px))"
---

# Design System: Além do Óbvio

## Overview

**Creative North Star: "O Olhar Clínico"**

O design se comporta como o olhar do Dr. Ritchie diante de um rosto: escuro ao redor, luz só onde importa, e linhas finas que medem e explicam. A página é uma sequência de cenas de cinema em fundo preto de sala, com o ouro velho reservado para o que deve ser visto: a tese, o número, o botão, o traço de análise. O resultado é editorial e cerimonial, mas preciso; nada é decorado sem motivo.

A densidade é baixa e a escala é dramática. Títulos em Bodoni Moda chegam a 176px com itálico para a palavra que carrega o sentido; o corpo em Manrope fica em 17px e cinza pergaminho, recuado. Cada seção é uma cena com uma ideia, separada por linhas finas de osso translúcido, e o movimento de rolagem conta a história: créditos que acendem letra por letra, foco que sai do desfoque, um rolo de filme que desliza.

A assinatura visual é "O olhar do Doutor": traços dourados de análise (terços, eixos, pontos) desenhados sobre fotos reais, com uma lente circular que acende a imagem sob o cursor. Ela é a tese transformada em imagem e deve ser a referência de qualquer elemento novo.

**Key Characteristics:**
- Preto de sala como palco; osso como texto; ouro velho como única cor de destaque.
- Serifa de alto contraste em escala de cartaz, com itálico como ênfase.
- Linhas finas de 1px no lugar de caixas, cartões e sombras.
- Cenas de tela inteira com uma ideia cada e rolagem como linha do tempo.
- Grão de filme fixo sobre tudo (img/grao.png a 34% de opacidade).
- Uma única quebra de tom: a cena dos três dias em fundo osso.

## Colors

Uma paleta de sala escura: quase preto, osso quente e um único ouro envelhecido, sem segunda cor de marca.

### Primary
- **Ouro Velho** (ouro-velho): a cor da visão. Tese em itálico, números de autoridade, marcas da autoavaliação, traços de análise, foco e seleção, e o botão principal. Aparece em pequenas áreas; a raridade dá o valor.
- **Ouro Claro e Ouro Fundo** (ouro-claro, ouro-fundo): só existem juntos, como topo e base do gradiente vertical do botão principal (180deg, ouro-claro → ouro-velho 48% → ouro-fundo).
- **Ouro Escuro** (ouro-escuro): o ouro para fundo claro. Usado no "05" em itálico da cena osso, onde o ouro velho perderia contraste.

### Neutral
- **Preto Sala** (preto-sala): fundo de toda a página, do topo ao rodapé. Também é a cor de seleção de texto sobre ouro.
- **Superfície Câmara** (superficie-camara): fundo do diálogo do formulário, um degrau acima do preto.
- **Rolo de Filme** (rolo-filme): faixa do rolo de fotos da turma.
- **Barra Noturna** (barra-noturna) e **Miolo Escuro** (miolo-escuro): fundo da barra fixa inferior e o círculo escuro da mira dentro do botão.
- **Osso** (osso): texto principal sobre preto e fundo da cena dos três dias.
- **Cinza Pergaminho** (cinza-pergaminho): texto de apoio, rótulos em itálico, legendas e parágrafos secundários.
- **Tinta Osso** (tinta-osso): texto sobre o fundo osso.
- **Texto sobre Ouro** (texto-sobre-ouro): rótulo do botão principal.
- **Linha Fina** (linha-fina): todos os divisores de 1px, bordas de lista e o trilho do medidor.
- **Erro Coral** (erro-coral): mensagem de erro do formulário, a única cor fora da família.

### Named Rules
**The Ouro Raro Rule.** O ouro velho marca só o que tem sentido: a palavra-chave, o número, a ação, a seleção, o traço de análise. Nunca vira fundo de seção, borda decorativa ou cor de texto corrido.

**The Uma Quebra Rule.** A página tem uma única cena em fundo osso (os três dias). Uma segunda cena clara dilui a quebra; telas novas ficam no preto.

## Typography

**Display Font:** Bodoni Moda (com Didot, Bodoni 72, Georgia)
**Body Font:** Manrope (com system-ui)
**Label/Mono Font:** IBM Plex Mono (com ui-monospace)

**Character:** Uma serifa didone de cartaz, alto contraste e itálico expressivo, contra uma sans geométrica e calma. A Bodoni fala; a Manrope explica; a mono mede.

### Hierarchy
- **Display** (400, clamp 46–96px, entrelinha 0.98, -0.03em): a tese no título de abertura, com a segunda frase em ouro itálico e recuada. Acima dela, a marca "Além do *Óbvio*" em Bodoni clamp 26–36px. O nome do Doutor usa clamp 64–170px. No celular, a tese fica em clamp 38–64px.
- **Headline** (400, clamp 40–96px, 1.02): títulos de cena (h2). Variantes de cena ficam entre clamp 40–88px; a palavra de sentido vai em itálico.
- **Title** (400, clamp 28–40px, 1.1): itens numerados, títulos de cartão (28px na grade de incluídos) e perguntas do FAQ (clamp 21–28px, 1.25).
- **Eyebrow** (Bodoni itálico, clamp 17–20px, 1.3, cinza pergaminho): o rótulo acima de cada título, sempre em itálico e nunca em caixa alta.
- **Body** (Manrope 400, 17px, 1.65; 16px no celular): texto corrido, limitado a 62ch (`.medida`) e 44–52ch em blocos de apoio.
- **Label** (Manrope 500, 13.5–14px, cinza pergaminho): rótulos de campo, legendas de número, créditos.
- **Mono** (IBM Plex Mono, 10–11px, 0.16–0.2em, caixa alta): só instrumentos, como o medidor FOCO, os créditos de canto e as anotações dos traços.
- **Números de palco** (Bodoni 400, até clamp 110–320px, entrelinha 0.78, numerais alinhados e tabulares): placar de prática, dias 04/05/06 e números de autoridade.

### Named Rules
**The Itálico com Sentido Rule.** O itálico marca a palavra que carrega a tese ou o dado ("visão", "Óbvio", o dia do meio). Nunca uma frase inteira, nunca enfeite.

**The Mono É Instrumento Rule.** IBM Plex Mono só aparece onde algo é medido ou anotado. Não serve para rótulos de seção nem botões.

## Layout

Cenas de tela inteira empilhadas, cada uma com uma ideia. A margem lateral é fluida (clamp 20–72px) e o respiro vertical padrão de cena é 140px (160/140px na cena osso, 120px nos casos). Seções de texto usam grades assimétricas de duas colunas (5/7, 7/5, 4/8, 6/5 frações) com vão clamp 40–120px; o título da coluna menor fica fixo (sticky, top 120px) enquanto a lista ao lado rola. Depoimentos usam grade de 12 colunas com foto e citação alternando de lado.

Cenas de assinatura ficam presas na tela enquanto a rolagem avança (visão, rolo de filme), e fotos ocupam até 64–70vw com máscara em gradiente que dissolve na página. Abertura, Doutor e convite final são de altura total com texto ancorado embaixo.

Em 860px ou menos todas as grades viram uma coluna, os títulos fixos se soltam, os números do Doutor vão para duas colunas e o retrato lateral some. Em 560px ou menos os campos em dupla do formulário empilham.

## Elevation & Depth

O sistema é plano por camadas tonais e luz, não por sombras. A profundidade vem de fotos que dissolvem em preto com máscaras e gradientes, do grão de filme fixo e de paralaxe leve nas fotos de palco. As únicas sombras são funcionais e ficam em elementos que flutuam sobre o conteúdo.

### Shadow Vocabulary
- **Brilho do botão** (inset 0 1px 0 rgba(255,255,255,.42), inset 0 -1px 0 rgba(0,0,0,.2), 0 14px 34px -18px rgba(201,163,90,.45)): relevo sutil e halo dourado curto no botão principal; no hover, halo maior (0 18px 40px -16px a .55).
- **Flutuação** (0 20px 50px rgba(0,0,0,.6)): só a barra fixa inferior, junto do contorno dourado interno.
- **Contorno interno** (inset 0 0 0 1px): borda desenhada por sombra em botões fantasma, chips e barra; osso a .22–.32 em repouso, ouro velho ao selecionar ou passar o mouse.
- **Traço legível** (drop-shadow 0 0 2px rgba(0,0,0,.7)): sob os traços de análise, para lerem sobre a foto.

### Named Rules
**The Plano por Padrão Rule.** Superfícies não têm sombra. Sombra só existe em botão principal e no que flutua sobre a página.

**The Desfoque Não É Brilho Rule.** O estado fora de foco é um desfoque real (filter: blur) do texto em ouro translúcido, nunca um halo de text-shadow.

## Shapes

Três formas e nada entre elas: o retângulo reto (raio 0) para fotos, campos, diálogo e blocos de texto; a pílula (999px) para tudo que se clica; o círculo (50%) para marcas, a mira do botão, o anel da autoavaliação e a lente do olhar. Bordas são linhas de 1px; as fotos são cortadas a frio, em 3/2, 4/5 ou 3/4, ou dissolvidas por máscara.

**The Três Formas Rule.** Nada de cantos de 4, 8 ou 12px. Se não é pílula nem círculo, é reto.

## Components

Contidos e precisos: linhas finas, pouco volume, e só o botão principal brilha.

### Buttons
- **Shape:** pílula (999px), altura mínima de 60px, rótulo alinhado à esquerda e uma "mira" circular de 44px à direita.
- **Primary:** gradiente vertical de ouro (ouro-claro → ouro-velho → ouro-fundo), texto Manrope 600 15px em texto-sobre-ouro. A mira é um círculo miolo-escuro com uma retícula dourada de traço fino.
- **Hover / Focus:** brilho +6%, halo dourado maior, a retícula gira 90° e reduz enquanto o núcleo dourado acende. No desktop o botão segue levemente o cursor. Foco visível: contorno de 2px em ouro velho, afastado 4px.
- **Ghost:** pílula translúcida (preto a .35) com desfoque de fundo e contorno osso de 1px; no hover, texto e contorno em ouro velho. Usado no topo fixo.
- **Barra fixa:** pílula barra-noturna no canto inferior direito (centralizada e na largura menos 32px no celular), contorno dourado a .5 e sombra de flutuação, mira em ouro sólido com retícula escura. Aparece ao rolar e some na cena da visão, na autoavaliação, no convite final e sempre que outro botão estiver na tela.

### Chips
- **Style:** pílulas com contorno osso a .22, texto 14px, padding 9×17px, usadas nas perguntas de escolha do formulário.
- **State:** selecionado ganha contorno ouro velho, fundo ouro a .14 e texto ouro; foco com contorno de 2px.

### Cards / Containers
- **Corner Style:** reto (0).
- **Background:** nenhum; o "cartão" é um bloco com linha fina no topo ou na base.
- **Shadow Strategy:** nenhuma (ver Elevation & Depth).
- **Border:** linha-fina de 1px dividindo itens, grades e FAQ.
- **Internal Padding:** 30–36px no eixo vertical; numeração em Bodoni itálico cinza (01, 02…).

### Inputs / Fields
- **Style:** só a linha de baixo (1px osso a .28), fundo transparente, texto 17px, sem raio.
- **Focus:** a linha passa para ouro velho; sem brilho.
- **Error:** resumo no topo do formulário com filete coral à esquerda e mensagem em erro-coral (13.5px) embaixo de cada campo com problema; a linha do campo e o contorno das opções ficam coral. Caixa de aceite no mesmo anel dourado da autoavaliação.
- **Diálogo:** retângulo superficie-camara com borda osso a .16, até 640px, fundo escurecido a .82 com desfoque de 6px.

### Navigation
- **Topo:** logo à esquerda (34px; 28px no celular) e botão fantasma à direita, sobre o palco transparente. Ao rolar ganha fundo preto a .93 com desfoque de 14px e linha fina embaixo.

### O olhar do Doutor (assinatura)
Fotos reais escurecidas (brilho .42, saturação .35) quando ativas, com traços de análise em ouro velho de 1.2px que se desenham em 1.2s: linhas de terços e eixos, pontos sólidos, tracejado 4/5 e anotações em mono 10px caixa alta. Uma lente circular (raio 120px) segue o cursor e mostra a foto nítida, com anel dourado e marcas de mira.

### Autoavaliação
Lista de afirmações separadas por linha fina, cada uma com uma marca circular de 22px em contorno dourado que se preenche ao marcar; o item marcado fica em ouro. Ao lado, um anel fino de 320px (220px no celular) que se completa em ouro com a contagem em Bodoni 96px.

## Do's and Don'ts

### Do:
- **Do** manter o fundo em preto-sala e reservar o ouro velho para tese, número, ação, seleção e traço de análise.
- **Do** escrever títulos em Bodoni Moda 400 com itálico só na palavra de sentido, e rótulos de seção em Bodoni itálico cinza pergaminho.
- **Do** separar conteúdo com linhas de 1px em linha-fina, não com caixas.
- **Do** usar pílula para tudo que se clica, círculo para marcas e retângulo reto para o resto.
- **Do** usar fotos reais da turma, recortadas a frio ou dissolvidas em preto por máscara.
- **Do** desenhar elementos novos de explicação no vocabulário do olhar do Doutor: traço dourado fino, ponto, tracejado e anotação mono.
- **Do** dar a cada movimento uma versão quieta para quem prefere menos animação (a classe fx-reduzido).

### Don't:
- **Don't** criar uma segunda cor de destaque ou uma segunda cena em fundo osso.
- **Don't** usar raios intermediários (4, 8, 12px) ou cartões com fundo e sombra.
- **Don't** pôr brilho ou sombra fora do botão principal e da barra fixa.
- **Don't** usar IBM Plex Mono em rótulos de seção, botões ou texto corrido.
- **Don't** escrever títulos em caixa alta ou em Manrope.
