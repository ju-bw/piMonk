# Raspberry Pi

ju -- https://bw1.eu -- 3-Nov-18  

Raspberry Pi Kochbuch\footfullcite{monk_raspberry:2014} Quelle \cite{monk_raspberry:2014}

Elektronik-Hacks\footfullcite{monk_elektronik_hacks:2013} Quelle \cite{monk_elektronik_hacks:2013}

Action-Buch\footfullcite{monk_action_buch:2016} Quelle \cite{monk_action_buch:2016}



![raspberryPi-3-001](img/raspberryPi-3-001.pdf)

## Vergleich zwischen Arduino C und Python

| **Befehl**          | **Code in Arduino C**    | **Python-Code**         |
|:--------------------|:-------------------------|:------------------------|
|Konstante definieren |const int ledPin = 9;     | ledPin = 18            |
|Pin als Ausgang      |pinMode(ledPin,OUTPUT)    | GPIO.setup(ledPin,GPIO.OUT)|
|Ausgang auf high     |digitalWrite(ledPin,HIGH);| GPIO.output(ledPin,True)   |
|Ausgang auf low      |digitalWrite(ledPin,LOW); | GPIO.output(ledPin,False)  |
|Verzögerung in [s]   |delay(1000);              | time.sleep(1)           |