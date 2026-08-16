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
