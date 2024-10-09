# Documentação do index.html
## Visão Geral da Estrutura HTML
O arquivo `index.html` é o ponto de entrada principal do site. Ele utiliza HTML5 `(<!DOCTYPE html>)` e segue princípios de estrutura semântica.

### Declaração do Tipo de Documento
```html
<!DOCTYPE html>
<html lang="pt-BR">
```
Isso declara o documento como HTML5 e define a linguagem para Português (Brasil).

`Seção Head`
```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mundo Invertido | Semana Front-end</title>
  <link rel="stylesheet" href="assets/css/styles.css" />
</head>
```
A seção `<head>` inclui metadados para codificação de caracteres, compatibilidade e configurações do viewport. Também define o título da página e liga para o arquivo de folha de estilo externo.

### Conteúdo do Corpo
```html
<body class="light-theme" aria-label="O site está utilizando o tema light" role="body">
  <!-- Conteúdo do cabeçalho -->
  <!-- Conteúdo principal -->
  <!-- Conteúdo do rodapé -->
</body>
```
O corpo contém três seções principais: cabeçalho, conteúdo principal e rodapé.

`Seção Cabeçalho`
```html
<header>
  <audio id="music" autoplay>
    <source src="assets/musics/normal-world.mpeg" aria-details="Audio do site" />
  </audio>

  <div class="header-content">
    <img class="invert-element" src="assets/images/banner/logo.svg" alt="Imagem principal Mundo Invertido. Semana Frontend DIO." />
    <p class="invert-element" role="text">
      Uma jornada para quem não tem medo do desconhecido. O caminho para o Mundo invertido é incerto, repleto de obstáculos e perigos. Porém, a recompensa é grande: salvar Hawkings e o mundo todo das garras de Vecna. Você está preparado? Então clique no botão abaixo para entrar no Mundo Invertido!
    </p>
    <button id="switch-theme-button" onclick="switchTheme()">Inverter Mundos</button>
  </div>

  <div id="top-characters" class="world-characters"></div>
</header>
```
O cabeçalho contém:

- Um player de áudio em autoplay
- Uma imagem do logo
- Um parágrafo descritivo sobre a jornada
- Um botão para alternar o tema
- Um contêiner para personagens superiores
`Seção Conteúdo Principal`
```html
<main>
  <div id="bottom-characters" class="world-characters"></div>

  <!-- Seções -->
  <section id="section-inverted-world" class="container">
    <!-- Conteúdo do Mundo Invertido -->
  </section>
  <section id="section-stranger-things-trailer" class="container">
    <!-- Conteúdo do Trailer de Stranger Things -->
  </section>
  <section id="section-stranger-things-gallery">
    <!-- Conteúdo da Galeria de Stranger Things -->
  </section>
  <section id="section-form" class="container">
    <!-- Conteúdo do Formulário Dungeons & Dragons -->
  </section>
</main>
```
A seção de conteúdo principal contém quatro seções:

- Mundo Invertido
- Trailer de Stranger Things
- Galeria de Stranger Things
- Formulário Dungeons & Dragons
- Cada seção tem sua própria estrutura única e propósito.

`Seção Rodapé`
```html
<footer>
  <p>
    Projeto construído para fins didáticos, com o objetivo de colocar em prática os conhecimentos de HTML, CSS e JavaScript aprendidos na DIO.
  </p>
  <img src="assets/images/footer/logo.svg" alt="Logotipo DIO" />
</footer>
```
O rodapé contém uma descrição do projeto e o logo da DIO.

### Características de Acessibilidade
O documento inclui várias características de acessibilidade:

- Estrutura HTML semântica adequada
- Uso correto dos atributos alt para imagens
- Uso de atributos role para melhor suporte ao leitor de tela
- Texto descritivo para botões e links
### Recursos Externos
O documento depende de recursos externos:

- Folha de estilo: `styles.css`
- Script: `main.js`
- Arquivos de imagem e áudio localizados na pasta `assets`
Esta documentação abrangente cobre a estrutura, propósito e componentes-chave do arquivo `index.html`, fornecendo um panorama claro da configuração e funcionalidade do site.
