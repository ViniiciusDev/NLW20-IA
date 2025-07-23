# HTML

- HyperText
  - Texto puros, livros, Resvistas, Jornais.
  - Links: Acessar outros Documentos
  - Imagens, Vídeos, Áudios
- Markup
  - Marcação 
  - Composto por Tags: <a> Link </a>
  - Contém Atributos: <a href="https://rocketseat.com.br">
    - Encontramos Atributos Globais: id, class, ...
- Language
  - Linguagem 
  - Sintaxe: Maneira de escrever.

# HTTP
  
  - HyperText
  - Transfer
    - Transferência
  - Protocol
    - Protocolo
    - Conjunto de Regras

    -> HTTP corresponde ao Protocolo de transferência de HyperText.
  METHODS HTTP: GET, POST, PATCH/PUT, DELETE
  HEADERS: Se trata de instruções/informações extras para cada chamada.

# URL
    
    - Uniform
      - Uniforme
    - Resource
      - Recurso
    - Locator
      - Localizador
      -> Usado para Encontrar recursos ( html, css, js, pdf, mp3, mp4, png ...)

# IP

  - Internet
    - Rede Mundial de computadores
  - Protocol
    - Conjunto de Regras
    -> Corresponde ao Endereço do nosso computador.

    123.32.1.23 (IP) -> Port: 80

# DNS

  - Domain
    - Domínio
  - Name
    - Nome
  - Server
    - Servidor

    rocketseat.com.br (Domain) -> Port 443

    -> Criamos um nome único para "Substituir" o nosso ip tornando mais fácil lembrarmos o nome da busca. 

# Estrutura HTML

  - Encontramos o <!DOCTYPE html> -> Informa que se trata do tipe de arquivo html.
  - Tag <html></html> Dentro dele ficar definida toda a estrutura da nossa página, conhecido como ROOT (Nó)
  - Dentro do html encontramos os filhos <head></head> e <body></body>
  - No <head></head> encontramos os Meta dados, que são informações necessárias para a página que ficaram escondidas com a função de somente configurar nossa página.

# CSS

  - Cascading
    - Cascata
    - Regras das escritas
    - Hierarquia
    - Especificidade
  - Style
    - Estilo
  - Sheet
    - Folha

  -> De um arquivo que terá na sua sintaxe, declarações, propriedades e valores, apartir disso, o HTML é impactado visualmente

  # Box Model

    -> Tudo para o CSS é considerada uma caixa e cada caixa possui as seguintes propriedades:
      - Espaçament Interno: Padding
      - Bordas: Border
      - Espaçamento externo: Margin
      - Conteúdo: Content
      - Largura: Width
      - Altura: Height

# REM vs Px

-> Pixel é o menor valor de uma tela. 
-> REM ele pega o valor em pixel da nossa Root. Tendo como base o valor de 1rem = 16px

# JAVASCRIPT 

  - Linguagem de Programação.
  - Usado no Browsers
  - Input -> Process -> Output

    -> Inputs: São conservados em variáveis que é uma memoria que armazena dados.
    -> Process: Muitas vezes usamos Functions para processar, agrupar e possibilitar o reuso do código.
      - Possui uma sequência lógica e depois retorna uma Saída.

  - Dentro da programação temos o envolvimento de novas estruturas sendo elas:
    - Estrutura de dados.
    - Estrutura de Decisão.

    -> Algoritmo: Consiste na sequência de passos de maneira ordenada, afim de chegar a alguma conclusão (limitada)

# DOM 
  - Document
  - Object
  - Model

# API 
  
  - Application
  - Programming
  - Interface

  -> Usamos o JSON para realizar essa comunicação.
  JSON: Javascript Object Notation

  -> API usam as regras HTTP para realizar essas comunicações conforme os protocolos da internet. 

# CDN
  - Content
  - Delivery
  - Network

# LLM
  - Large
  - Language 
  - Model 

# Agentes AI
 - Tools (Ferramentas): Permitem o uso de código ou apps, ou qualque informação extra.
 - Melhora o Contexto

 # Engenharia de Prompt 
 - One Shot: Única pergunta sem muito contexto. 
 - Few Short: è apresentado exemplos do que se espera. 
 - Chain of Thought: Cadeia de pensamento para a IA responder gradativamente conforme a instrução.