## Lokaverkefni (30%)

**Gerðu eftirfarandi verkefni (e. tutorials):**
  - Settu upp í TinkerCad
  - Settu upp verklega með brauðbretti og íhlutum
  - Svaraðu spurningum.

1. Skoðaðu [Vélbúnaður og blink: Ladyada´s lesson 0, 1 og 2](https://learn.adafruit.com/series/ladyadas-learn-arduino) og svaraðu eftirfarandi spurningum: (**4%**)

   1. Hvað er þetta á Arduino og hlutverk þess?
![ARduino Uno](https://github.com/GunnarThorunnarson/Verksmidja1/blob/master/Myndir/Arduino.png)
   1. Að hvaða leyti er gagnapinni 13 sérstakur í Arduino Uno?
   1. Hver er munurinn á digtial og analog input pinnum?
   1. Hjá sumum digital pinnum er tilda merki (~) fyrir PWM. Hvað er e. Pulse Width Modulation (PWM) og fyrir hvað er það notað?

2. Pushbutton (Digital Input) í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**4%**)

   1. _Hverju myndi það breyta ef við myndum tengja viðnám fyrir hnappinn í 5V í staðinn fyrir jörð (GND)?_
   1. _Afhverju þarf pinni 2 að vera tengdur við jörð?_
   1. _Breyttu kóðanum þannig að með að ýta á takkann þá ser slökkt á LED ljósi sem myndi annars lýsa stöðugt._

3. Potentiometer (Analog Input) í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**4%**)
   1. _Arduino er með 10 bita analog to digital converter (ADC). Hvernig virkar ADC og hvaða gildi er verið að vinna með?_
   1. _Hvað gerist ef við tengjum digital skynjara við analog pinna?_

4. Using the Serial Monitor í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**4%**)
   1. _Hvað þýðir 9600 baud í Serial.begin(9600) og hvað gerist ef þú breytir gildinu?_

5. Photoresistor (Analog Input) í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**4%**)
   1. _Útskýrðu færibreyturnar og gildin í map fallinu. Afhverju þarf úttakið í analogWrite að vera á bilinu 0-255?_<br>
       `analogWrite(9, map(sensorValue, 0, 1023, 0, 255));`

6. Ultrasonic Distance Sensor í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**5%**)
    1. _Breyttu kóðanum þannig að hann vinnur eingöngu með sentimetra._
    1. _Hvað gerir timeout í eftirfarandi falli? `pulseIn(pin, value, timeout);`_

7.  Project 6: Light Theremin (hátalari og ljósviðnám) í [TinkerCad Projects](https://www.tinkercad.com/learn/circuits/projects) (**5%**)
    1. _Hvað er verkhlutfall (e. duty cycle) og hvernig tengist það tíðni (e. frequency)?_
    1. _Tíðni (e. frequnzy) er mæld í Hertz (Hz). Útskýrðu hvernig það er gert._


### Námsmat og skil
Gefið er heilt fyrir fullnægjandi lausn og svör, hálft ef ábótavant eða svör vanta.
Skilaðu á Innu vefslóð á Github wiki vefsíðu sem inniheldur:

1. TinkerCad tengla á lausnir (muna að hafa public).
2. [Skjámyndbandsupptöku](https://screencast-o-matic.com) af virkni í TinkerCad.
3. Myndbönd af virkni úr verklegum tilraunum.
4. Svör við spurningum.

