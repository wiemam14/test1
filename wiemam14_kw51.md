# *Protokoll KW 51*

  Name: Markus Wieser   
  Klasse: 4AHME   
  Datum: 19.12.2017   
  Anwesend: Tuttner Raphael, Waltl Kilian, Wieser Markus    
  Abwesend: Strauß Lukas, Strutz Sebastian, Uhl Christian, Waltl Kilian, Zitz Karlheinz
  
  ## **Modbus**
  
  Das Kommunikationsprotokoll des Modbus ist ein zustandsloses Protokoll, welches auf dem Request/Response Prinzip aufgebaut ist.
  Der große Vorteil des Modbus-Protokolls liegt darin, dass sich andere Geräte mit unterschiedlichen Verbindungstechnologien miteinander verbinden lassen.

Es gibt drei unterschiedliche Varianten zur Datenübertragung:

* Modbus ASCII   (textuelle byteweise Übertragung)     
* Modbus RTU     (Remote Terminal Unit, binäre byteweise Übertragung)      
* Modbus TCP     (Übertragung in TCP Paketen)   

## **Tabellen des Modbus Daten-Modells**

* Discrete Inputs  -> Ein einzelnes Bit welches nur gelesen werden kann (z.B. Taster).    
* Coils            -> Ein einzelnes Bit welches gelesen und beschrieben werden kann (z.B. LED).     
* Input Register   -> Ein 16 Bit Wert welcher nur gelesen werden kann (z.B. Temperatursensor).    
* Holding Register -> Ein 16 Bit Wert welcher gelesen und beschrieben werden kann.    
