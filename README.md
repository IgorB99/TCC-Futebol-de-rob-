# TCC-Futebol-de-rob-

## Descrição do projeto: 
### Objetivo: 
Desenvolver em um ambiente controlado e monitorado por uma câmera, com visão computacional baseada na biblioteca multiplataforma OpenCV, onde dois robôs irão receber comandos baseados nos dados da câmera, que serão enviados através de uma rede de comunicação utilizando NodeMCU, simulando uma partida de futebol.
### Metas:

• Identificar imagens recebidas através da câmera

• Analisar o posicionamento da bola e dos robôs

• Gerar um comportamento individual para cada robô

• Realizar a comunicação entre os robôs através de um servidor mqtt

### Recursos:

• Node MCU ESP8266

• Motores DC 5V

• Ponte H L298N

• Camera

• Computador com acesso a rede internet

NodeMCU: O módulo Wifi ESP8266 NodeMCU é uma placa de desenvolvimento que combina o chip ESP8266, uma interface usb-serial e um regulador de tensão 3.3V. A linguagem de programação será MicroPython.

Driver motor ponte H: possui dois canais e permite controlar velocidade e sentido de rotação de até dois motores ao mesmo tempo.

A programação basea-se nos conceitos de MQTT, onde um computador realizará a função de *broker*, a camera terá a ligação de *publisher* e os robos terão a ligação de *subscriber* recebendo os dados.
