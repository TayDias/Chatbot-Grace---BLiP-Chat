# GRACE
Documentação de sistema do chatbot desenvolvido.

<img width="300" alt="Logo do bot" src="https://github.com/TayDias/Chatbot-Grace---BLiP-Chat/blob/79d7ec9703362ff72fe0f8e77a4be3394c3dc465/general/grace.jpg">

Acesso ao Bot em produção: http://bot.pectem.com


## Sistema de diretórios

* \blip
  * \flow1.json
  * \flow2.json
  * \flow3.json
* \watson
  * \entities
    * file.csv
  * \intents
    * file.csv
* \general
  * \grace.jpg
  * \configRouter.png
  * \configcontextobots.png
  * \configPrincipalAtendimento.png


Acesso ao Blip: https://portal.blip.ai/application


## Instruções

* Criação dos três subbots e importação dos fluxos na pasta \blip
* Configuração do roteador no Blip
* Configuração do Watson Assistant
* Configuração de ambiente do builder dos subbots


## Configuração do roteador do Blip

Incluir os subbots de acordo com as nomenclaturas para "Serviço":

<img width="1001" alt="Router" src="https://github.com/TayDias/Chatbot-Grace---BLiP-Chat/blob/79d7ec9703362ff72fe0f8e77a4be3394c3dc465/general/configRouter.PNG">


## Configuração do Watson Assistant

Criar modelo e importar entidades e intenções contidas na pasta /watson


## Configuração de ambiente do builder dos subbots

Habilitar o contexto de roteador e o traking em todos os subbots nas configurações gerais:

<img width="400" alt="Contexto" src="https://github.com/TayDias/Chatbot-Grace---BLiP-Chat/blob/79d7ec9703362ff72fe0f8e77a4be3394c3dc465/general/configcontextobots.PNG">


Ainda nas configurações gerais, incluir as variáveis de configuração de conexão com o Watson:

urlWatson: valorDaURL,
authorizationWatson: valorDaChave


Habilitar o Blip Desk no subbot Principal em Atendimento:

<img width="1001" alt="Contexto" src="https://github.com/TayDias/Chatbot-Grace---BLiP-Chat/blob/79d7ec9703362ff72fe0f8e77a4be3394c3dc465/general/configPrincipalAtendimento.PNG">
