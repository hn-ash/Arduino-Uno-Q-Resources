\# Basic LED Example



\## What this does

Blinks onboard LED



\## Steps

1\. Upload code

2\. Run program



\## Output

LED blinks every second





Open code file:

BATnotepad examples\\basic-led\\code.inoShow more lines

Paste:

void setup() {

&#x20; pinMode(LED\_BUILTIN, OUTPUT);

}



void loop() {

&#x20; digitalWrite(LED\_BUILTIN, HIGH);

&#x20; delay(1000);

&#x20; digitalWrite(LED\_BUILTIN, LOW);

&#x20; delay(1000);

}

