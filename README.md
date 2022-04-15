# Estacao_Meteorologica
PCB desenvolvida para aquisição de dados meteorológicos e envio via rede Lora

	|---------------- ESTAÇÃO METEOROLÓGICA ----------------|
	|  							|
	|		   ITENS REMOVÍVEIS:			|
	|-------------------------------------------------------|
	| - RFM95 915MHZ: RÁDIO LORA;				|
	| - BME280: SENSOR TEMPERATURA, UMIDADE E PRESSÃO; 	|
	| - GUVA S12SD: SENSOR DE RAIOS UV;			|
	| - ESP32 DEVKIT V1: NODEMCU 30 PINOS;			|
	| - PLUVIÔMETRO DE BÁSCULA;				|
	|-------------------------------------------------------|
	|							|
	|		  PINOUT ESP32 DEVKIT V1:		|
	|-------------------------------------------------------|
	|  D2  - PUSH BUTTON PULL UP;				|
	|  D15 - SIG GUVA S12SD;				|
	|  D21 - SDA BME280;					|
	|  D22 - SCL BME280;					|
	|  D13 - LED;						|
	|  D25 - INPUT PULL UP 1;				|
	|  D33 - INPUT PULL UP 2;				|
	|  D34 - DI02 RFM95;					|
	|  D35 - DI01 RFM95;					|
	|  D26 - DI00 RFM95;					|
	|  D19 - MISO RFM95;					|
	|  D27 - MOSI RFM95;					|
	|  D5  - SCK  RFM95;					|
	|  D18 - CSS  RFM95;					|
	|  RX2 - RST  RFM95;					|
	|-------------------------------------------------------|
	|  MATEUS CORDEIRO					|
	|  C.MATEUS@ALUNO.IFSP.EDU.BR				|
	|-------------------------------------------------------|
