<!-- SEED: re-run /impeccable document once there's code to capture the actual tokens and components. -->

# Design System: Mulher Inesquecível

## 1. Overview

**Creative North Star: "O Refúgio Dourado"**

Uma estética que acolhe como um abraço e convence como uma conversa íntima. O design é propositalmente feminino sem ser infantil, sofisticado sem ser frio, emocional sem ser apelativo. As referências visuais partem de https://ddn.janehansen.com.br/ — mesma vertical de relacionamento — mas elevam o padrão estético com uma paleta completa de rosa antigo, dourado e neutros quentes.

**Key Characteristics:**
- Elegância como credibilidade — cada pixel comunica valor
- Feminino sem estereótipo — rosa como poder, não como fragilidade
- Hierarquia emocional guiada por movimento coreografado
- Contraste deliberado entre acolhimento visual e urgência de copy

## 2. Colors

**The Complete Palette Rule.** A paleta tem 4 papéis de cor deliberados, cada um com função distinta. Nenhuma cor é decorativa — cada uma serve à hierarquia emocional da página.

### Primary
- **Rosa Antigo** (`[to be resolved]`): A cor da identidade. Usada em backgrounds de seções de acolhimento, bordas de cards de depoimento, e como tom base da hero. Evoca calor, empatia, força feminina.

### Secondary (Accent)
- **Dourado** (`[to be resolved]`): A cor da ação e da transformação. Usada no CTA principal, em detalhes de preço, selo de garantia, e destaques de bônus. Comunica valor e urgência sem agressividade.

### Neutral
- **Branco Sujo / Off-White** (`[to be resolved]`): Background principal da página. Mais quente que branco puro, menos arenoso que bege. Base para texto e containers.
- **Quase Preto** (`[to be resolved]`): Cor do texto corporal, com um toque de tom quente para suavizar o contraste sem perder legibilidade WCAG AA.

### Tertiary
- **Verde Menta Suave** (`[to be resolved]`): Cor de confirmação, garantia, selos de segurança. Aparece em badges de "Garantia 7 dias" e checkmarks.

### Named Rules
**The One Voice Rule.** A cor dourado ocupa ≤10% de qualquer seção. Sua raridade é o que a faz funcionar. Se dourado aparece demais, vira ruído.

## 3. Typography

**Display Font:** Serifa (`[font pairing to be chosen at implementation]`)
**Body Font:** Sans-serif humanista (`[font pairing to be chosen at implementation]`)

**Character:** O contraste entre uma display serifada dramática (para títulos de hero e seções emocionais) e uma sans humanista quente (para corpo e labels) cria a tensão certa entre sofisticação e acessibilidade. A serifa carrega o peso emocional; a sans mantém a página legível em celular.

### Hierarchy
- **Display** (light, `[to be resolved]`, 1.0): Títulos de hero e CTAs principais. Uso exclusivo para momentos de alto impacto.
- **Headline** (regular, `[to be resolved]`, 1.2): Títulos de seção. A serifa em peso menor que display.
- **Title** (medium, `[to be resolved]`, 1.3): Subtítulos e chamadas internas.
- **Body** (regular, `[to be resolved]`, 1.6): Texto corrido. Limitar a 65–75ch.
- **Label** (medium, `[to be resolved]`, uppercase): Botões e badges.

## 4. Elevation

Coreografado → camadas com profundidade sutil. A página usa sombras leves para criar camadas de informação: cards de depoimento elevam-se ligeiramente acima do fundo, o CTA tem uma elevação maior (quase flutuante), e seções alternam entre planas e elevadas para guiar o olhar. Sem gradientes ou glassmorphism — a profundidade vem de sombras quentes e sobreposições de cor.

## 5. Components

*Nenhum componente implementado ainda. Serão extraídos na próxima execução de `/impeccable document` quando houver código.*

## 6. Do's and Don'ts

### Do:
- **Do** usar rosa antigo como cor de acolhimento em backgrounds e bordas
- **Do** usar dourado com moderação — ≤10% da seção
- **Do** manter contraste WCAG AA (4.5:1 corpo, 3:1 texto grande)
- **Do** usar movimento coreografado para revelar conteúdo em scroll
- **Do** usar serifa dramática para momentos de alto impacto emocional

### Don't:
- **Don't** usar gradientes roxo-azul ou laranja/preto de marketing digital genérico
- **Don't** usar Inter, system-ui ou sans-serif genérica como fonte display
- **Don't** usar glassmorphism, neon ou efeitos de brilho
- **Don't** usar cinza puro em texto — sempre tintar com o tom quente
- **Don't** usar cards aninhados ou contagens regressivas agressivas
- **Don't** usar pure white (#FFFFFF) como fundo — preferir off-white quente
