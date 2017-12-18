# *Protokoll KW40*

## **AVR-Studio**

  Name: Markus Wieser   
  Klasse: 4AHME   
  Datum: 26.09.2017   
  Anwesend: Strutz Sebastian, Tuttner Raphael, Uhl Christian, Waltl Kilian, Wieser Markus, Zitz Karlheinz
  
  ### Mikroprozessor
  
  Ein Prozessor ist eine elektronische Schaltung, welche mit Hilfe von Befehlen Schaltungsteile steuert.  
  Die Besonderheit des Mikroprozessors liegt darin, dass alle Funktionen auf einem Microchip gefertigt sind.  
  Grundsätzlich gibt es zwei verschiedene Arten der Speicherverwaltung. Es gibt die Neumann und Harvard-Architektur.  
  Bei der Neumann-Architektur sind Befehle und Daten im gleichen Speicher.  
  Im Gegensatz zur Harvard-Architektur, bei welcher diese physikalisch getrennt sind.
  
  
  ### **Komponenten eines µC´s**
  
  ALU -> Das Rechenwerk (Arithmetic Logic Unit) ist eine digitale Schaltung, das arithmetische/logische Befehle ausführt.   
  
  Register -> Das Register ist eine Speichereinheit welche mit der Recheneinheit verbunden ist. (Daten, Operanten, Ergebnisse)  
  
  Steuerwerk -> Das Steuerwerk ist für die Abarbeitung des Programmes zuständig.  
  							Hier befinden sich der Program-Counter und der Befehls-Decoder. 
  
  Reset -> Hierbei wird die CPU in einen definierten Zustand gesetzt. Der Programcounter erhält den Wert der Programmstartadresse und            die Bits im Status Flag Register werden in einen Grundzustand gebracht.
  
  Takt -> Der Takt ist für die Bestimmung des zeitlichen Ablaufs (auch Clock genannt).
  
  Program-Counter -> Er wird bei jedem neuen Programmablauf aktualisiert.
  
  ### *Atmel Studio*
  
  Das Atmel Studio (auch AVR Studio) ist eine Open-Source Entwicklungsumgebung für die Programmierung von AVR-Mikroprozessoren. 
  Es basiert auf der Visual Studio Shell von Microsoft und besteht aus einer Projektverwaltung, einem Editor einem Debugger und   Werkzeugen zum Beschreiben der µC´s.  
  
  Mit dem Atmel Studio kann man in C aber auch in Assembler programmieren. Weiters kann man die Ausfürhung des Programms simulieren.
  
 ### *Stack*
 
 Der Stack-Speicher funktioniert nach dem Last in First Out Prinzip. Dies bedeutet das Daten von unten noch oben abgelegt werden und auch nur so gelesen werden können.     
 Befehle für den Stack: 
 
 push -> Schiebt Daten auf den Stack. (Stackpointer wird verringert)       
 pop -> Holt die oberste Datei vom Stack.(Stackpointer wird erhöht)   
 call -> Speichert den aktuellen Wert des Program-Counters.
 
 ### *Stackpointer*
 
 Der Stackpointer zeigt immer auf den obersten freien Platz im Stack. Ein Stackoverflow entsteht wenn kein Speicher mehr frei ist und danach anstatt des Stacks in den Heap gespeichert wird. Dabei ist es sehr wahrscheinlich das es zu einem Systemabsturz kommt.
 
 
### *Besprochene Befehle*

JMP -> Führt einen unbedingten Sprung durch   
RJMP -> Führt einen relativen Sprung durch    
LDI -> Lädt einen Wert in ein Register    
PUSH -> Schiebt Daten in den Stack    
POP -> Holt Daten vom Stack   
CLR -> Setzt ein Register auf 0     
OUT -> Überträgt Daten vom CPU-Register ins I/O Register     
SER -> Setzt alle Bits ins Register   
STD -> Holt einen Wert vom Register zurück      
IN -> Holt einen Wert aus dem I/O Register      
LDD -> Holt einen Wert aus einem Register     
SUBI -> Subtrahiert ein Register      


 
### *Produktdaten des ATmega328p*

Frequenz: 16MHz     
CPU-Register: 32  
Flash Speicher: 32kB    
EEPROM: 1kB   
SRAM: 2kB 


 
 
 
 
 
 
 
 
  
  
  
