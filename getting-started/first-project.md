\# First Project: Blink LED



\## Steps



1\. Open App Lab

2\. Add code:



void setup() {

&#x20; pinMode(LED\_BUILTIN, OUTPUT);

}



void loop() {

&#x20; digitalWrite(LED\_BUILTIN, HIGH);

&#x20; delay(1000);

&#x20; digitalWrite(LED\_BUILTIN, LOW);

&#x20; delay(1000);

}



3\. Upload and run



\## Output

LED should blink every second

