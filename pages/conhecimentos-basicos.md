# Conhecimentos básicos

## Hardware
Em tecnologia da informação (TI), hardware é a parte física da máquina, ou seja, é todo o equipamento mecânico interno (placa mãe, placa de video, processador, etc.) ou externo (gabinete, monitor, mouse, teclado) de um computador.

## Software
Software é a parte lógica, ou seja, são programas e/ou conjunto de instruções a serem seguidas e executadas pelo computador (editores de textos, jogos, drivers de dispositivos, firmware, etc.). Software podem ser classificados em dois tipos principais, chamados de Software de sistema e Software aplicativo.

### Software de sistema
Ele é como se fosse uma camada intermediária entre o usuário e o hardware. É um software de extrema importância, pois administra os componentes de hardware e disponibiliza um ambiente para que outros softwares funcionem normalmente. O software do sistema auxilia o usuário e o hardware a executar funções e interagir um com o outro. Basicamente, é um tipo de software que gerencia o comportamento do hardware do computador para fornecer aos usuários as funções básicas necessárias.

Abaixo estão alguns softwares que fazem parte dessa classificação:

- **Firmware**: é um conjunto de instruções embutidas diretamente no hardware. O firmware fornece instruções de como um dispositivo se comunica com outro hardware. O firmware é armazenado na ROM flash. Embora ROM(read only memory) seja uma memória de somente leitura, a ROM flash pode ser apagada e reescrita, pois é um tipo de memória flash, permitindo atualizações do firmware.
- **Sistemas Operacionais**: um conjunto de softwares que visa gerenciar recursos e ser uma camada de abstração do hardware para o usuário. Será melhor explicado em um próximo conteúdo!
- **Drivers**: é um software que possibilita um dispositivo específico se comunicar com o sistema operacional. Drivers podem ser necessários tanto para dispositivos internos (placa de vídeo e unidade de mídia óptica), quanto para externos (monitor e impressora). Atualmente o hardware está vindo com a tecnologia *plug and play*, o que significa que o hardware funciona sem a instalação de drivers. Mesmo o sistema operacional reconhecendo o hardware, a instalação de drivers corretos pode fornecer opções e funções adicionais ao dispositivo.
- **Tradutores de linguagem de programação**: tradutor ou processador de linguagem de programação é um software que converte linguagem de programação de alto nível para linguagem de máquina(binário), fazendo com que a CPU (central processing unit) possa entender as instruções passadas para ele. Existem 3 categorias de tradutores:  compilador, interpretador e assembler.
    - **Compilador**: transforma (compila) todo o código-fonte para código de máquina (binário) e salva o código compilado em um arquivo executável. Depois do processo de compilação você pode executar o arquivo. Por já ter um código na linguagem de máquina a execução torna-se mais rápida.
    - **Interpretador**: ao contrário do compilador que transforma todo o código-fonte para código de máquina e só depois pode ser executado, o interpretador transforma o código-fonte em código binário e executa simultaneamente. O interpretador lê a primeira linha, transforma essa linha para código de máquina e a executa, depois faz o mesmo processo para a próxima linha e para o restante do código-fonte. Esse processo acaba sendo mais demorado que o compilado, pois basicamente são três operações ocorrendo simultaneamente: leitura, transformação de um código para outro e execução.
    - **Assembler**: funciona da mesma maneira que o interpretador, a única diferença é que um assembler só converte código escrito na linguagem assembly para código de máquina.
- **Softwares utilitários**: são programas criados para otimizar, configurar, manter e facilitar a utilização do sistema operacional (gerenciador de arquivos, drivers, ferramenta de backup, analisador de discos, etc.).

### Software aplicativo
São programas que executam tarefas específicas e são voltados para o usuário final (editores de texto, jogos, navegadores, etc.). Algumas categorias de software aplicativo:
- **Software de banco de dados**: são programas com a função de gerenciar banco de dados. Alguns exemplos:
    - Clipper
    - MySQL
    - FileMaker
- **Processadores de palavras**: programas para criação e edições de documentos. Alguns exemplos:
    - Microsoft Word
    - Google Docs
    - Libre Office Writer
- **Softwares gráficos**: como o próprio nome diz, são programas para edições gráficas, como edição de vídeo, foto e outros. Alguns exemplos:
    - Adobe Photoshop
    - GIMP
    - Inkscape
- **Web browsers**: aplicativos criados para navegar na internet. Alguns exemplos:
    - Google Chrome
    - Firefox
    - Brave browser
- **Software educacional**: programas com o intuito de auxiliar o aprendizado. Alguns exemplos:
    - Anki
    - Libre Office Math
    - Delta Drawing
- **Software multimídia**: programas que executam tarefas como: tocar uma música, reproduzir um vídeo, entre outros. Exemplos de software multimídia:
    - VLC Media Player
    - Dragon Player
    - Elisa

## Linguagens de alto e baixo nível
### Alto nível
São linguagens que têm uma sintaxe mais próxima da linguagem humana. Elas possuem um nível de abstração maior, por isso na maioria delas você não precisa ter conhecimentos aprofundados do hardware para fazer tarefas básicas, facilitando o entendimento e uso da linguagem.
### Baixo nível
É a famosa linguagem de máquina (binário), com ela você consegue comunicar diretamente com o hardware, já com uma linguagem de alto nível não é possível ou pelo menos é mais trabalhoso. Pelo fato de conseguir se comunicar diretamente com o hardware, você precisa de conhecimentos sobre a arquitetura e funcionamento dos componentes internos de um computador.

O termo *linguagem de baixo nível* não se refere apenas à linguagem binária, mas sim às linguagens que se tem uma sintaxe mais próxima da linguagem binária.

*OBS. Caso você ouça alguém falando que um software é de baixo nível, é porque ele atua próximo ou diretamente com o hardware e também provavelmente foi escrito com linguagens de baixo nível. O mesmo vale para software de alto nível, só que inverso.*

---
