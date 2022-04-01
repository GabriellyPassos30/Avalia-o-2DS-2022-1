# Avaliação 2DS-2022-1

### Requisitos para avaliação:
#####   1) Criar um repositório no GitHub chamado Avaliação Teórica Mobile

#####   2) Criar um arquivo Markdown formatado e com as respostas para os seguintes questionamentos:



_1. Descreva a arquitetura do sistema operacional Android_

São Divididas em 6 camadas

- System Apps: Seria o próprio sistema do android em si, ao qual vem aplicativos já instalados de fábrica como por exemplo: Telefone, Câmera, Calendário seria a camada a qual o usuário teria contato direto.

- Java API Framework: gerenciador de tarefas com intuito de organizar as casas, Sendo base para criação de APIS para aplicações e recursos.

- Native C/C+ Libraries:Possui os serviços que efetua as aplicações básicas do dispositivo como  aumentar brilho, abrir, câmera. Entre outras. Sendo a base que utiliza de biblioteca em c++  e c.

- Android RunTime: Onde fica localizada Android Runtime(ART) que executa máquinas virtuais em dispositivos de baixa performance e memória e a Dex direcionada a Android, diminuindo consumo de memória.

- Hardware Abstraction Layer(HAL):abstrai e acessa ao núcleo possuindo interface para acessar componentes.

- Linux Kenel: Seria o núcleo onde Ficam os Drivers e Power management onde seria a parte a qual desliga ao celular.

_2. Descreva como desenvolvemos interfaces em aplicações Android nativas em Kotlin_

Utilizamos como base o aplicativo android studio para realizar aplicações em Kotlin.

_3. Defina o que é uma View_

Seria a forma a qual o usuário visualiza aos dados, como ficaria estaticamente sem alterar ao código. 

_4. Defina o que é um Event Listener_
 
 Podemos usar como evento como por exemplo clicar no botão, seria como configuramos de forma especifica  e assim quando efetuamos esse evento ele efetua a busca da componente. 

_5. Defina o que é o Graddle_

Gerenciador de dependências de arquivos, faz atualização normalmente de forma automática é um arquivo binário. Possui a ser propenso a ocorrer erros.

_6. Escreva o que é o SDK Android_

Ferramenta designada para desenvolvedores e programadores com objetivo de criar apps para android ou IOS a qual se adapta a qual tipo de equipamento seja de Celular a tablets 

_7. Escreva o que são API level, e dentro das configs de build o que é Target API e minimal API level_
-  API level : Faz identificação das versões do Android.
-  Target API : A  API compartilha as informações entre si como por  exemplo Facebook que linka com Instagram, não sendo os mesmos aplicativos mais compartilhando informações.
-  Minimal API level :possui o objetivo de proporcional melhor experiência ao usuário, impedindo que usuário consiga baixar arquivos incompatíveis com determinadas versões. 

_8. O que é o processo de Build_

Efetua a compilação do arquivo para retificar os componentes, evitando que ocorra erros no arquivos.

_9. Descreva como podemos testar aplicações Android em nossos próprios celulares._

Conseguimos efetuar uma aplicação desenvolvida para android,No próprio computador usando aplicativos como GenyMotion ou 
habilitando  celular em celulares Android ativando o modo desenvolvedor para assim iniciaremos a Depuração USB, através do cabo conectado pelo cano no Computador e Celular.

