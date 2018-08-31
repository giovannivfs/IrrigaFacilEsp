# Documento de Fincionalidades

## Requisito 1 - Comunicação entre Celular e placa Arduíno.
  O celular devera se conectar a placa de Arduíno através de rede Wifi conectada a placa, para assim poder efetuar as funções.

## Funcionalidade 1 - Requisito 1
* Sendo um usuário conectado à rede do Arduíno;
* Posso Acessar o sistema via Web ou App;
* Para Utilizar o Equipamento;

**Cenário 1. Conectado com Sucesso**
Dado que o Celular está conectado ao Arduíno e o estado do sistema consta como conectado, quando atuo conectando à rede do equipamento      então o sistema emite uma mensagem de "conectado", e o equipamento conecta - se ao celular.

**Cenário 2 - Falha na Conexão**
Dado que o equipamento não está conectado a rede quando executo qualquer função do equipamento então o sistema transmite uma mensagem para o equipamento e o equipamento retorna uma mensagem que não foi possível encontrar o equipamento na rede ou mostra uma mensagem de que o equipamento não respondeu.

## Requisito 2 - Enviar Comandos para Equipamentos
Os comandos serão disparados através de app no celular ou via Web para ligar e desligar.
