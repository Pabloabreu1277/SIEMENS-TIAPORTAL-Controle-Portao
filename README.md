# SIEMENS-TIAPORTAL-Controle-Portao
Projeto: Sistema de Controle de Porta de Garagem:  Descrição: O sistema de controle da porta deve abrir e  fechar a porta por meio de um painel de botões e  fornecer recursosde segurançapara evitaracidentes.


 Funcionalidades:
 • Pressionar Botão_Abrir abre a porta, desde que não esteja aberta.
 • Pressionar Botão_Fechar fecha a porta, desde que não esteja fechada.
 • A porta para de abrir quando o Sensor_Porta_Aberta é acionado.
 • A porta para de fechar quando o Sensor_Porta_Fechada é acionado.
 • Se o Feixe_Segurança detectar um objeto, a porta para de se mover

  Entradas:
 I0.1 -Botão para abrir a porta.
 I0.2 -Botão para fechar a porta.
 I0.3 -Sensor que indica se a porta está totalmente aberta.
 I0.4 -Sensor que indica se a porta está totalmente fechada.
 I0.5 -Sensor infravermelho para detectar objetos obstruindo a porta.
 Saídas:
 Q0.1 -Controla o motor para abrir a porta.
 Q0.2 –Controla o motor para fechar a porta
 Material
 CPU 1214C DC/DC/DC - Work memory 100 KB; 24VDC power supply with DI14 x 24VDC SINK/SOURCE, DQ10 x 24VDC and AI2 on board; 6 high-speed counters and 4 pulse outputs on board; signal board expands on-board I/O;
 up to 3 communication modules for serial communication; up to 8 signal modules for I/O expansion; 0.04 ms/1000 instructions; PROFINET interface for programming, HMI and PLC to PLC communication
 
<div  align="center"> 
  <div style="display: inline_block"><br>
    <img align="center" height="600" alt="coding-time" src="clpI_O.png">
