# DC-motor
## Run Hbrage with DC motor using Arduino using Tinker cad:
## code:
```
/ C++ code

void setup()
{
  pinMode(11, OUTPUT);
  pinMode(9, OUTPUT);
}

void loop()
{
  digitalWrite(11, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(9, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
![Screenshot 2024-08-01 001818](https://github.com/user-attachments/assets/a71319a0-96f2-477d-82c3-e603b6de6646)

