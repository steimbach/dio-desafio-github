﻿\# TCP/IP

- Protocolos de comunicação entre computadores em rede

- Transmission Control Protocol - Protocolo de Controle de Transmissão

- Internet Protocol - Protocolo de Internet

- Modelos de camada

- 4 Camadas - 1. Física (ex: placa de rede), 2. Rede (ex: IP), 3. Transporte (ex:TCP, UDP), 4. Aplicação(ex: FTP, SMTP, HTTP)

​		\*\*UDP\*\*

- Rápido
- Não confiável
- Carro do ovo
- LivestreamTcp

​				\*\*TCP\*\*

- Voltando à conexão
- Handshake
- Integridade, ordem dos dados
- Aplicativo de mensagens de texto

​			\*\*Ports\*\*

- As "portinhas" por onde os dados sairão e chegarão
- 20: FTP
- 22: SSH
- 25: SMTP
- 53: DNS
- 80: HTTP
- 443: HTTPS

​			\*\*Modem\*\*

- Modulator-demodulator
- Hardware que converte dados em um formato que possa ser transmitido de um computador para o outro e lido por outro.

​	   	 \*\*Roteador\*\*

- Distribui internet para um ou mais dispositivos de uma rede
- Pode fazer a comunicação entre redes
- Pode ser "burro"

​			\*\*Switch\*\*

- Distribui internet para um ou mais dispositivos de uma rede
- Criado para ser "inteligente"

​								\*\*Exercício Final\*\*

P: O Gmail costuma usar portas próprias, que não são padrões de SMTP e POP3. Tente descobrir quais são.

R: Gmail, os dados específicos do servidor SMTP do Gmail são:

- servidor SMTP: smtp.gmail.com;
- porta de saída: 465, caso esteja usando SSL ou 587 se for TLS.

P: O programador que trabalha com a Internet costuma usar banco de dados, como MySQL, e, claro, servidor web, como o Apache. Que tal você se adiantar e já descobrir quais são as portas usadas por estes sistemas?

R: O MySQL usa a porta 3306 por padrão. Já o Apache utiliza a porta 443.

