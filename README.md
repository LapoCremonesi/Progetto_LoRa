# Istruzioni per progetto LoRa

### Materiali
 - esp32
 - Moduli LoRa
 - Rock pi 4 SE
 - Sensori vari

### Moduli 
#### Librerie per utilizzare l'esp32 con il rock pi oppure solo il rock pi
 - ##### ESP32 con rock pi
    - eventuali librerie per i sensori
    - [ArduinoJson](https://techtutorialsx.com/2017/04/26/esp32-parsing-json/)
    - [LoRa](https://randomnerdtutorials.com/esp32-lora-rfm95-transceiver-arduino-ide/)
 - #### rock pi 4 SE 
    - [Python LoRa](https://github.com/chandrawi/LoRaRF-Python)
    - [Python Json](https://www.w3schools.com/python/python_json.asp)
    - [Python Flask](https://www.programmareinpython.it/blog/come-usare-il-web-framework-flask/)

### Procedimento
Per il procedimento di questo progetto si va ad utilizzare degli esp32 che permettono di comunicare tramite i moduli LoRa.
Oppure si può evitare di utilizzare un esp32 utilizzando la libreria LoRa per python.
Però almeno un esp deve esserci per permettere la raccolta e l'invio dei dati al rock pi ( server ).
Per un eventuale comunicazione esterna si andrà ad attivare il port forwarding in modo da fare richieste HTTP all'API interna del rock pi, in modo da comandare e monitorare tutti i vari sensori anche da remoto.
