# ROADMAP

```
Crie uma aplicação web em um único arquivo HTML, executável diretamente no navegador, para apresentar visualmente o raciocínio de um vídeo ou aula.

## Objetivo

A aplicação deve funcionar como um mapa mental/apresentação visual que me ajude a desenvolver o assunto enquanto gravo o vídeo.

O mapa deve mostrar a evolução do meu raciocínio de forma visual e organizada. A pessoa que estiver assistindo ao vídeo deve conseguir acompanhar a linha de pensamento apenas olhando para a tela.

## Tema

[TEMA DO VÍDEO]

## Conteúdo

Estruture o mapa a partir destas ideias:

[COLE AQUI OS TÓPICOS, ARGUMENTOS, EXEMPLOS E CONCLUSÕES]

Organize o conteúdo hierarquicamente, identificando:

* ideia central
* principais argumentos
* subargumentos
* exemplos
* comparações
* problemas
* causas
* consequências
* conclusão

Não é necessário utilizar todas essas categorias. Escolha a estrutura que fizer mais sentido para o assunto.

## Aparência visual

Utilize exclusivamente este padrão visual:

* Background principal: #123C47
* Cor de destaque: #FF6B00
* Branco: #FFFFFF
* Preto: #000000

A interface deve ter aparência moderna, minimalista e tecnológica, com estética de apresentação profissional.

Evite aparência de dashboard administrativo.

O conteúdo deve ser o protagonista.

## Regra importante sobre a interface

Não exiba textos explicativos sobre a própria aplicação.

Não mostrar:

* "Mapa mental para condução do vídeo"
* "Pergunta central"
* "Ideia principal"
* "Arraste para navegar"
* "Scroll para zoom"
* "Clique aqui"
* legendas explicando como utilizar a aplicação
* instruções de navegação
* textos técnicos sobre a interface
* qualquer texto que explique o funcionamento do mapa

A aplicação deve parecer uma apresentação pronta para ser exibida ao público.

Os títulos e textos devem pertencer exclusivamente ao conteúdo do tema.

## Layout

Crie uma ideia central visualmente destacada e organize os demais tópicos ao redor dela.

Utilize linhas ou conexões para mostrar claramente a relação entre os assuntos.

Evite excesso de elementos.

Priorize:

1. leitura rápida
2. hierarquia visual
3. conexão entre ideias
4. espaço negativo
5. aparência profissional

Os textos dos nós devem ser curtos. Quando uma explicação for necessária, utilize no máximo 1 ou 2 frases curtas.

Não transforme o mapa mental em um slide cheio de texto.

## Interatividade

A aplicação deve permitir:

* zoom
* navegação pelo mapa
* arrastar o mapa
* enquadrar o conteúdo
* retornar à visualização inicial

Esses recursos devem existir de forma discreta e não devem aparecer como instruções para o usuário.

Se houver controles visuais, mantenha-os pequenos, minimalistas e discretos.

Também deve ser possível usar a aplicação em tela cheia sem que elementos da interface atrapalhem a apresentação.

## Experiência durante a gravação

O mapa deve funcionar bem em uma gravação de vídeo.

Quando estiver enquadrado, o conteúdo principal deve ocupar a maior parte da tela.

As conexões entre os tópicos devem ser fáceis de acompanhar.

O mapa deve permitir que eu faça zoom em uma determinada região enquanto desenvolvo aquele ponto do assunto.

A navegação deve ser suave.

## Conteúdo

Não invente argumentos técnicos ou informações que não estejam no conteúdo fornecido.

Você pode reorganizar, resumir e melhorar a estrutura das ideias para criar uma narrativa visual mais clara.

Quando houver uma sequência lógica, represente essa sequência visualmente.

Quando houver comparação, represente os dois lados de maneira visualmente distinta.

Quando houver causa e consequência, represente essa relação claramente.

Quando houver uma conclusão, faça com que ela tenha destaque visual.

## Entrega

Entregue um único arquivo:

`mapa_mental.html`

O arquivo deve ser totalmente autocontido, sem necessidade de servidor, framework, biblioteca externa ou instalação de dependências.

Deve funcionar simplesmente abrindo o arquivo no navegador.

Antes de finalizar, verifique se:

* o HTML é válido
* todos os elementos aparecem corretamente
* o mapa pode ser navegado
* o zoom funciona
* o layout não fica cortado
* o conteúdo pode ser apresentado em tela cheia
* não existem textos ou elementos explicando como utilizar a aplicação
* não existem elementos visuais desnecessários
* as cores utilizadas seguem o padrão visual informado
```

# SLIDES

```
Crie uma aplicação web de apresentação em formato OnePage, executável diretamente no navegador, usando apenas HTML, CSS e JavaScript em um único arquivo HTML.

Conceito
A aplicação deve funcionar como uma apresentação semelhante ao PowerPoint, porém em formato vertical.
Cada seção da apresentação deve ocupar exatamente 100% da viewport, funcionando como um slide.
A navegação principal deve acontecer através do scroll vertical. Ao rolar a página, o sistema deve fazer uma transição suave para o próximo ou para o slide anterior, criando a sensação de que cada slide "sobe" ou "desce" na tela.
O usuário deve conseguir acompanhar uma linha de raciocínio visualmente, como se estivesse assistindo a uma apresentação.

Identidade visual
Utilize exclusivamente esta paleta principal:

Background principal: #123C47
Cor de destaque: #FF6B00
Branco: #FFFFFF
Preto: #000000
O background predominante deve ser #123C47.
Utilize #FF6B00 para elementos de destaque, títulos importantes, linhas, indicadores, ícones, números, estados ativos e elementos interativos.
Utilize #FFFFFF para textos principais e elementos que precisam de alto contraste.
Utilize #000000 somente quando fizer sentido visualmente, evitando excesso.
A estética deve ser:

Minimalista
Tecnológica
Moderna
Brutalista
Elegante
Alto contraste
Poucos elementos por tela
Tipografia grande
Forte hierarquia visual
Bastante espaço negativo
Aparência profissional
Evite aparência de template genérico de PowerPoint.

Estrutura dos slides
Cada slide deve possuir:

Altura mínima de 100vh
Largura de 100vw
Conteúdo centralizado verticalmente
Grid visual consistente
Tipografia responsiva
Hierarquia clara entre título, subtítulo e conteúdo
Cada slide deve representar uma etapa do raciocínio.
Não coloque excesso de informação em uma única tela.
O conteúdo deve entrar progressivamente, permitindo que o usuário compreenda a apresentação apenas olhando para a tela.

Navegação
Implemente:

Scroll vertical com comportamento suave
CSS scroll-snap para alinhar cada slide à viewport
Navegação por teclado usando Arrow Up, Arrow Down, Page Up, Page Down, Home e End
Navegação por mouse
Suporte a touch/mobile
Indicador lateral mostrando em qual slide o usuário está
O slide ativo deve possuir destaque visual usando #FF6B00
O indicador deve permitir clicar diretamente em qualquer slide
Não permita que pequenos movimentos do mouse façam a apresentação pular vários slides.
A navegação deve parecer controlada e intencional.

Animações
Os elementos de cada slide devem possuir animações de entrada quando o slide se tornar ativo.
Utilize animações como:

Fade in
Fade up
Fade down
Scale
Slide
Blur progressivo
Transformações sutis
As animações devem ser rápidas e elegantes.
Evite animações exageradas.
O objetivo é criar sensação de apresentação profissional, não de site cheio de efeitos.

Interação com o mouse
Os elementos interativos devem responder visualmente ao movimento do mouse.
Implemente efeitos como:

Hover
Pequeno deslocamento seguindo o cursor
Scale sutil
Mudança de brilho
Mudança de borda
Alteração de opacidade
Efeito de profundidade/parallax muito sutil
Glow utilizando #FF6B00
Cards e elementos importantes podem reagir ao movimento do mouse utilizando uma pequena rotação 3D baseada na posição do cursor.
Esses efeitos devem ser sutis e nunca prejudicar a leitura.

Efeito de cursor
Crie, se fizer sentido, um cursor visual customizado utilizando CSS/JavaScript.
O cursor pode possuir:

Pequeno ponto central
Anel externo
Expansão ao passar sobre elementos interativos
Mudança de estado em links, cards e botões
O cursor customizado deve desaparecer automaticamente em dispositivos touch.

Parallax
Utilize parallax de forma extremamente sutil.
Elementos decorativos do background podem se mover em velocidades diferentes conforme o movimento do mouse ou scroll.
Não transforme a apresentação em uma animação excessiva.
O conteúdo principal deve permanecer estável e legível.

Elementos visuais
Utilize recursos como:

Linhas finas
Grids
Círculos
Pontos
Blocos geométricos
Números grandes
Indicadores
Pequenos elementos técnicos
Microtipografia
Bordas finas
Glow discreto em #FF6B00
Esses elementos devem funcionar como elementos de composição visual.
Não utilize imagens apenas para preencher espaço.

Tipografia
Utilize uma fonte moderna e legível.
Priorize fontes sans-serif.
Os títulos devem ser grandes e fortes.
Use diferentes pesos tipográficos para criar hierarquia.
Sempre mantenha excelente contraste entre texto e background.

Responsividade
A apresentação deve funcionar corretamente em:

Desktop
Notebook
Tablet
Smartphone
No mobile:

Reduza tamanhos tipográficos proporcionalmente
Preserve a hierarquia visual
Ajuste grids para uma coluna
Remova ou simplifique efeitos que possam prejudicar performance
Desative o cursor customizado
Preserve a navegação por swipe/scroll
Performance
A aplicação deve ser leve.
Não utilize frameworks ou bibliotecas externas sem necessidade.
Priorize:

CSS puro
JavaScript vanilla
CSS transforms
CSS transitions
IntersectionObserver
requestAnimationFrame quando necessário
Evite loops JavaScript desnecessários.
Respeite prefers-reduced-motion e reduza ou desative animações quando o usuário tiver essa preferência configurada no sistema operacional.

Arquitetura
Organize o HTML de forma clara:

Header/global controls
Navigation
Slides/sections
Footer/global information
Cada slide deve possuir um identificador único.
Exemplo:
slide-01
slide-02
slide-03
slide-04
Crie uma estrutura JavaScript que permita facilmente adicionar, remover ou reorganizar slides posteriormente.

Experiência final
A sensação final deve ser de uma apresentação premium.
O usuário deve sentir que está navegando por uma apresentação interativa, e não simplesmente por uma página web longa.
Cada scroll deve representar uma mudança de pensamento.
A composição visual deve conduzir os olhos do usuário para o elemento mais importante de cada slide.
Utilize #123C47 como identidade visual dominante e #FF6B00 como elemento de energia e destaque.

Importante
Entregue tudo em um único arquivo HTML.
Não utilize backend.
Não utilize build system.
Não utilize React, Vue ou outros frameworks.
O arquivo deve funcionar simplesmente abrindo-o diretamente no navegador.
Inclua comentários no código indicando onde posso alterar:

Cores
Tipografia
Conteúdo dos slides
Quantidade de slides
Velocidade das animações
Intensidade dos efeitos de mouse
Configurações de navegação
Antes de finalizar, teste mentalmente a experiência de navegação entre todos os slides e garanta que não existam conflitos entre scroll, snap, animações e navegação por teclado.
```
## THUMBNAILS

# YouTube Thumbnail — Strict Asset Preservation & Widescreen Composition

```
You are an award-winning Creative Director and Senior Brand Designer specialized in YouTube technology channels.

Your mission is NOT simply to create attractive thumbnails.

Your mission is to design thumbnails that belong to a unified visual identity, making every video instantly recognizable before the viewer even reads the channel name.

The visual identity must remain constant.

Only the content changes.

## CRITICAL IMAGE PRESERVATION RULE

**The supplied presenter photo is an immutable source asset.**

You MUST use the **original presenter image exactly as supplied**.

The presenter is NOT an image-generation subject.

The presenter is NOT a character to be recreated.

The presenter is NOT a face to be enhanced, redrawn, regenerated, beautified, retouched, or interpreted.

### Allowed operations on the presenter image

You may ONLY:

* Crop the original photograph.
* Scale the original photograph proportionally.
* Move and position the original photograph within the composition.
* Remove or mask the original background if necessary.
* Create a clean cutout/mask around the presenter.
* Place the original cutout over the designed background.
* Use the original pixels of the supplied photograph.

### Forbidden operations on the presenter image

**DO NOT generate, redraw, reconstruct, replace, or modify the presenter.**

Specifically, NEVER:

* Generate a new face.
* Alter facial structure.
* Change facial features.
* Change eyes, nose, mouth, ears, jaw, hair, beard, or skin.
* Change age.
* Change body shape.
* Change clothing.
* Change pose.
* Change expression.
* Change gaze direction.
* Change teeth.
* Change skin texture.
* Apply beauty retouching.
* Apply AI face enhancement.
* Apply face restoration.
* Apply generative fill to the presenter.
* Relight the face.
* Reconstruct missing areas.
* Change photographic characteristics.
* Stylize the presenter.
* Turn the presenter into an illustration.
* Turn the presenter into a 3D render.
* Generate a similar-looking replacement.
* Create a synthetic version of the presenter.

**Do not regenerate any part of the presenter.**

If background removal is required, remove ONLY the background pixels surrounding the presenter. Preserve the presenter pixels exactly as they appear in the supplied photograph.

### Identity Preservation Priority

The presenter's identity has absolute priority over visual perfection.

If the original photograph has imperfections, preserve them.

If lighting is imperfect, preserve it.

If the image is slightly soft, preserve it.

If the expression is imperfect, preserve it.

**Do not "fix" the presenter.**

A slightly imperfect original photograph is always preferable to an AI-generated or modified presenter.

Think of the presenter asset as a **photographic sticker that can be cut out and placed on the canvas**, not as something that can be regenerated.

---

# OUTPUT FORMAT

The final image MUST be:

**1920 × 1080 pixels**

**16:9 widescreen**

This is a YouTube thumbnail.

Do NOT output:

* square images
* portrait images
* vertical compositions
* 4:3 compositions
* 1:1 compositions
* alternative aspect ratios

The final canvas must be exactly **1920 × 1080**.

---

# Brand Mission

The visual identity must feel like a complete Design System similar to those used by GitHub, Stripe, Linear, Apple, Docker, Vercel and modern software companies.

The visual language communicates:

* engineering
* precision
* infrastructure
* technical authority

# Brand Personality

The channel represents:

* Cloud Engineering
* Platform Engineering
* DevOps
* Site Reliability Engineering
* Infrastructure
* Kubernetes
* Linux
* Automation
* Programming
* Node.js
* Go
* Python
* AWS
* Azure
* Artificial Intelligence
* Audio Technology
* Music Production
* Music Learning
* Engineering Mindset
* Professional Education

The brand personality is:

* Technical
* Confident
* Minimal
* Premium
* Industrial
* Rational
* Modern
* Authoritative
* Clean
* Human
* Approachable
* Never childish
* Never exaggerated
* Never sensationalist

# Visual Style

## Minimalist Technological Brutalism

Inspired by:

* industrial design
* engineering blueprints
* developer tools
* terminal interfaces
* old operating systems
* CAD software
* technical manuals
* network diagrams
* technical documentation
* Swiss grid systems
* modern SaaS branding

# Color System

Primary Background:

`#123C47`

Primary Accent:

`#FF6B00`

Support colors:

* White `#F3E5DA`
* Black `#1B1B1A`
* Neutral Gray `#C8CDD0`

Do not introduce additional accent colors unless they already naturally exist inside the supplied photographic or visual assets.

# Grid System

**The grid must remain consistent across every thumbnail.**

Use:

* safe margins around every border
* consistent spacing
* strong alignment
* deliberate proportions
* predictable positioning

Never randomly place objects.

The composition must feel engineered rather than artistic.

# Standard Layout

Use this structure unless the supplied assets make a small adjustment necessary:

### Upper Left

Main title.

### Upper Right

Minimal technical graphics.

### Center

Product or featured object.

### Right Side

Presenter.

### Lower Left

Supporting object if necessary.

### Lower Right

Negative space or subtle technical graphics.

The presenter should almost always remain on the right side to strengthen visual recognition across the channel.

# Background

Use a solid dark teal background:

`#123C47`

Allowed subtle textures:

* engineering grid
* technical blueprint lines
* architectural construction guides
* terminal coordinate markings
* extremely subtle noise texture
* minimal technical patterns

Never use:

* photographs as backgrounds
* landscapes
* rooms
* cities
* 3D environments
* gradients
* bright lights
* cinematic environments

# Typography

Typography is the hero.

Use only:

* JetBrains Mono
* Space Mono
* Share Tech Mono
* IBM Plex Mono
* SF Pro Display Bold
* Inter Black
* Helvetica Neue Bold

Titles should contain:

* 3–6 words
* maximum 7 words
* large font
* bold typography
* high contrast
* mostly uppercase

Primary title color:

`#FF6B00`

When necessary, place text inside rectangular white or black labels inspired by engineering documentation.

Never use rounded rectangles.

Never use playful typography.

# Presenter

The presenter photo is supplied as an external image asset.

**Use the supplied photograph. Do not generate a replacement.**

The presenter must remain visually identical to the supplied photograph.

The only acceptable transformation is:

**ORIGINAL PHOTO → CROP / MASK → POSITION ON CANVAS**

Do not perform:

**ORIGINAL PHOTO → AI REGENERATION → NEW PERSON**

The presenter should retain:

* original face
* original facial proportions
* original expression
* original eyes
* original mouth
* original hair
* original skin
* original clothing
* original pose
* original photographic appearance

Do NOT improve, beautify, stylize, relight, reconstruct, or reinterpret the presenter.

If background removal is necessary, use a precise cutout/mask.

The mask must follow the actual silhouette of the person.

Do not generate missing edges.

Do not invent hair strands.

Do not reconstruct clothing.

Do not alter the person's body.

### Presenter Position

Place the presenter predominantly on the right side of the composition.

Maintain enough breathing room around the face.

Never crop the face awkwardly.

Keep the eyes visible.

Do not cut through important facial features.

Do not distort the presenter.

Maintain the original aspect ratio of the photograph.

**No horizontal stretching.**

**No vertical stretching.**

**No face warping.**

**No body reshaping.**

# Guest

If another person is supplied:

Apply the exact same asset-preservation rules.

Use the supplied photograph as-is.

Only:

* crop
* scale proportionally
* mask
* position

Do not regenerate or modify the guest.

The guest should normally be smaller than the presenter unless the topic is specifically about that person.

# Products and Objects

One or more objects may be supplied.

Examples:

* servers
* computers
* microphones
* audio interfaces
* AWS logos
* Kubernetes logos
* terminal screenshots
* code snippets
* music equipment
* books
* electronics

Keep realistic proportions.

Use the supplied assets whenever available.

Do not unnecessarily regenerate supplied products or logos.

Avoid floating effects.

Optional monochrome treatment may be used when appropriate, but do not alter recognizable logos or important product details.

The object should reinforce the title.

Never compete with the presenter.

# Graphic Language

Allowed graphical elements:

* terminal cursor
* pixel cursor
* engineering arrows
* coordinate markers
* measurement guides
* technical annotations
* code brackets
* `</>`
* `[]`
* `_`
* thin waveform
* small crosses
* alignment guides
* blueprint markings

Keep every graphic minimal.

Every line must have a purpose.

# Visual Hierarchy

### Priority 1

Title

### Priority 2

Presenter

### Priority 3

Object

### Priority 4

Supporting graphics

The viewer should understand the thumbnail in under two seconds.

# Lighting

For generated background and graphical elements:

* soft
* controlled
* minimal
* technical

However:

**Do NOT apply lighting changes to the supplied presenter photograph.**

Do not relight the presenter.

Do not add artificial highlights to the face.

Do not create cinematic lighting on the presenter.

Do not apply orange-and-teal grading.

Do not apply HDR.

Do not apply bloom.

Do not apply lens flare.

# Cropping Rules

The entire composition must be designed for 1920×1080.

Respect safe margins.

For the presenter:

* use the original image
* crop only when necessary for composition
* preserve facial identity
* preserve natural proportions
* preserve the original appearance
* never crop through the face
* never distort the photograph

For all assets:

**Crop, scale and position. Do not regenerate.**

# Thumbnail Psychology

Create curiosity through clarity.

Do not create curiosity through confusion.

The thumbnail must immediately communicate:

* What is this about?
* Why should I care?
* What will I learn?

The thumbnail should feel trustworthy rather than sensational.

# Channel Consistency

Every thumbnail must appear to belong to the same design language.

The audience should recognize the channel after seeing only:

* colors
* typography
* spacing
* composition
* presenter placement
* graphic language

Imagine all thumbnails displayed together on the YouTube homepage.

They should look like chapters from the same book.

# ABSOLUTE ASSET RULE

The supplied photographs are **reference assets, not prompts for image generation**.

When a photograph of the presenter is provided:

**DO NOT recreate the photograph.**

**DO NOT reinterpret the photograph.**

**DO NOT improve the photograph.**

**DO NOT generate a new version of the photograph.**

**DO NOT modify the person.**

Instead:

**USE THE ORIGINAL IMAGE → REMOVE/MASK BACKGROUND IF NEEDED → CROP → SCALE PROPORTIONALLY → POSITION → COMPOSE.**

The presenter must remain the exact same person with the exact same visual appearance as in the supplied source image.

If there is any conflict between visual improvement and preservation of the original presenter, **preservation always wins**.

# Final Quality Check

Before producing the final image, verify:

1. Canvas is exactly 1920×1080.
2. Aspect ratio is exactly 16:9.
3. Presenter comes directly from the supplied photograph.
4. Presenter was only cropped, masked, scaled proportionally, and positioned.
5. Presenter was NOT regenerated.
6. Presenter face was NOT altered.
7. Presenter expression was NOT altered.
8. Presenter clothing was NOT altered.
9. No AI-generated face is present.
10. Background is dark teal `#123C47`.
11. Typography follows the specified system.
12. Title has maximum 7 words.
13. Presenter is predominantly on the right.
14. Composition follows the grid.
15. Visual hierarchy is clear.
16. No unnecessary visual effects are present.
17. The thumbnail remains readable at small size.

**If preserving the presenter requires sacrificing a visual effect, sacrifice the visual effect.**

**The original presenter photograph always takes priority.**

# Negative Prompt

Avoid:

* AI-generated presenter
* regenerated face
* altered face
* modified facial features
* face enhancement
* face restoration
* beauty retouching
* skin smoothing
* artificial skin
* changed expression
* changed eyes
* changed mouth
* changed hair
* changed clothing
* body modification
* face reconstruction
* generative fill on presenter
* synthetic person
* look-alike presenter
* replacement presenter
* stylized presenter
* illustrated presenter
* 3D presenter
* cinematic presenter
* relit presenter
* overprocessed presenter
* clickbait
* fake emotions
* gaming aesthetics
* cyberpunk
* heavy HDR
* oversaturated colors
* fire
* smoke
* explosions
* emoji
* comic style
* cartoons
* memes
* glassmorphism
* rounded cards
* random gradients
* glowing borders
* 3D icons
* colorful backgrounds
* busy compositions
* tiny text
* visual clutter

# Inputs

The following assets will be provided:

* Presenter photo
* Optional guest photo
* Product or object images
* Video title
* Topic description

**Use the supplied assets.**

Do not invent replacement photographic assets.

Do not generate a replacement presenter.

# Final Goal

Create a premium, clean, memorable, technical YouTube thumbnail in **1920×1080 (16:9)**.

The thumbnail should immediately communicate:

> "This is a serious engineering channel focused on Cloud, DevOps, Kubernetes, Infrastructure, Platform Engineering, Programming, Artificial Intelligence, Audio Technology, and Music."

The identity must remain constant.

Only the content changes.

**The presenter photograph must remain unchanged.**
```
