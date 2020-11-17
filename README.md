# BasicArduino
I'm going to learn how to use an Arduino, and make awesome things with it!


## TableofContents
* [TableOfContents](#TableOfContents)
* [HelloArduino](#HelloArduino)
* [FiniteLEDBlink](#FiniteLEDBlink)

## HelloArduino

### Description & Code

```C++
void setup() {
  
  pinMode(13, OUTPUT);
  Serial.begin(9600); // This turns on my Serial Monitor
  Serial.print("Hello World!");
}

void loop() {
  Serial.println("bonk");
  
  digitalWrite(13, HIGH);           
  delay(250);                       
  digitalWrite(13, LOW);            
  delay(250);                     
}

```

### Evidence
[Here is my code on Arduino Create](https://create.arduino.cc/editor/jslatos85/3b0ad2c4-bc00-4a20-8dff-e44b30f5417b)

### Image or Wiring
<img src="http://troybaverstock.com/wp-content/uploads/2019/04/arduino-servo-button-red-green-RGB-LED-wiring-diagram.png" width="300px" /> 

Image credit belongs to [Troy Baverstock](https://troybaverstock.com/learn/fritzing-circuit-diagrams/)

### Reflection
write a reflection here, remember that it should be usefull, not a diary entry.

## FiniteLEDBlink

### Description & Code

```C++
Code Goes Here
```

### Evidence

### Image or Wiring

### Reflection
