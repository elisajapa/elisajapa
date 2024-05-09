# SCULP - As melhores tattoos

Este é o código HTML para a página da web do SCULP, um site dedicado a mostrar e vender tatuagens temporárias. O código é bem organizado e compreensível, com seções distintas para o cabeçalho, a seção inicial, e a seção de projetos (tatuagens disponíveis).

## Cabeçalho

O cabeçalho contém o logotipo do SCULP e um menu de navegação simples.

- **Logo**: Um logotipo simples representando a letra "S".
- **Menu de Navegação**: Um link para a seção de projetos (tatuagens disponíveis).

## Seção Inicial

Esta seção contém um slideshow de imagens de tatuagens e informações sobre o SCULP.

- **Slideshow**: Uma série de imagens de tatuagens temporárias em rotação.
- **Informações**: Informações sobre o SCULP e uma breve descrição das tatuagens temporárias disponíveis. Também inclui links para redes sociais.

## Seção de Projetos (Tatuagens Disponíveis)

Nesta seção, são exibidas várias tatuagens temporárias disponíveis para compra.

- **Tatuagens**: Cada projeto é representado por uma imagem da tatuagem, o nome da tatuagem, uma descrição breve e um ícone representativo.
- **Links de Compra**: Cada projeto inclui um link para a página de compra da tatuagem.

## Referências Externas

- O código faz uso de fontes do Google Fonts para estilização de texto.
- Também utiliza ícones do Font Awesome para os links das redes sociais.

# Documentação CSS - SCULP

Aqui está a documentação do código CSS para a página da web SCULP, organizada por seções e propriedades CSS relevantes.

## Configuração Geral

- **html**: Define o esquema de cores e o comportamento de rolagem suave para a página.
- **body**: Define a fonte padrão, margens e largura máxima para o conteúdo da página, além do esquema de cores de fundo.

## Cabeçalho (`.cabecalho`)

- **Display**: Define o cabeçalho como um flex container para alinhar itens horizontalmente.
- **Logo**: Estiliza o logotipo com uma borda circular, transição e efeito de hover.
- **Menu de Navegação**: Estiliza os itens do menu e define o efeito de hover.

## Seção Inicial (`.home`)

- **Display**: Define a seção inicial como um flex container para posicionar elementos lado a lado.
- **Slideshow**: Estiliza o slideshow de imagens de tatuagens, definindo tamanho, animação de transição e tempo de rotação.
- **Informações**: Estiliza o bloco de informações sobre o SCULP, incluindo fonte, espaçamento e tamanho do texto.
- **Redes Sociais**: Estiliza os ícones das redes sociais com borda, tamanho e efeito de hover.

## Projetos (`.projetos`)

- **Container de Projetos**: Define o layout dos projetos como flexível, com espaçamento entre os itens e quebrando em várias linhas conforme necessário.
- **Projeto**: Estiliza cada projeto individualmente, incluindo tamanho máximo, posição relativa e efeito de hover.
- **Informações do Projeto**: Estiliza as informações do projeto, como título e descrição, com fundo escuro e opacidade variável ao passar o mouse sobre o projeto.
- **Botão de Mostrar Projetos**: Estiliza o botão para mostrar mais projetos, definindo tamanho, cor de fundo e efeito de hover.

## Outros

- **Animação de Gradiente**: Define uma animação para o fundo em gradiente, criando um efeito visual dinâmico.
- **Mensagem do Usuário**: Estiliza uma mensagem fixa na parte inferior da página, com fundo e texto coloridos.
- **Classes Ocultas**: Define uma classe para ocultar elementos da página quando necessário.
- **Botão de Aceitar Mensagem**: Estiliza o botão para aceitar a mensagem do usuário com cor de fundo, texto e efeito de hover.

Esta documentação fornece uma visão geral das diferentes partes do código CSS do SCULP, facilitando a compreensão de sua estrutura e estilo.

# Documentação JavaScript - SCULP

Aqui está a documentação do código JavaScript para a página da web SCULP, organizada por funcionalidades e métodos relevantes.

## Botão Mostrar Projetos

- **Funcionalidade**: Ao clicar no botão "Mostrar Mais Projetos", os projetos ocultos serão exibidos.
- **Evento**: Adiciona um ouvinte de evento ao botão para executar a função `mostrarMaisProjetos`.
- **Esconder Botão**: Adiciona a classe "remover" ao botão para ocultá-lo após clicar.
- **Mostrar Mais Projetos**: Adiciona a classe "ativo" aos projetos ocultos para exibi-los.

## Botão Aceitar Mensagem

- **Funcionalidade**: Ao clicar no botão "Aceitar Mensagem", a mensagem do usuário é ocultada.
- **Evento**: Adiciona um ouvinte de evento ao botão para executar a função `aceitaMensagem`.
- **Ocultar Mensagem**: Adiciona a classe "oculto" ao contêiner da mensagem do usuário para escondê-lo.
- **Armazenamento Local**: Armazena um valor indicando que o usuário aceitou a mensagem, para que ela não apareça novamente.

## Salvar Resultado no Histórico de Conversões

- **Funcionalidade**: Salva o resultado de uma conversão no histórico de conversões.
- **Parâmetro**: `conversao` - Objeto contendo os detalhes da conversão a ser salva.
- **Recuperar Histórico de Conversões**: Recupera o histórico de conversões armazenado localmente.
- **Armazenamento Local**: Armazena o histórico de conversões em formato JSON no armazenamento local.

Esta documentação fornece uma visão geral das diferentes funcionalidades e métodos do código JavaScript do SCULP, facilitando a compreensão de sua lógica e comportamento.

----------------------------------------------------------------------------------------------------------
                        Documentação feita por Elisa Lopes e Camila Alejandra.
