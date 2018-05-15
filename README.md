# projeto
projeto estufa


Descri��o do Projeto:

Sensor de umidade
Utilizar para monitorar tr�s diferentes n�veis de umidade do solo: Seco, �mido ou encharcado. A bomba ser� atuada de acordo com a classifica��o do estado do solo;

Bomba de �gua + Ponte H
Ser� controlada por PWM e um determinado tempo de atua��o (Timer). A bomba ser� acionada (ou n�o) ap�s verifica��o da estrutura condicional (Estado cr�tico?);

Bluetooth
Enviar� periodicamente (ou mediante detec��o de presen�a ou alta temperatura) as informa��es de todos os sensores contidos na planta, como umidade, luminosidade, temperatura, estado da bomba, presen�a de algu�m pr�ximo a planta;

Sensor de presen�a
Caso algu�m seja detectado nas proximidades da planta, imediatamente todas as informa��es de sensoriamento ser�o coletadas e enviadas via Bluetooth.

Sensor de temperatura
Caso a temperatura seja muito alta e o solo n�o esteja encharcado, a bomba atuar� brevemente de forma a �refrescar� a planta.
	
M�dulos Utilizados:

Sensor de Temperatura: BME280
Sensor de Umidade de solo: FC-28 *
Sensor de Ilumina��o: LDR 
Sensor de Presen�a: PIR BISS0001
Bluetooth: JDY09 AT09 *
Bomba de �gua: Submersible Pump 12VDC series *
Ponte H: L298 *

