# Arduino Buzzer Sound Code

This Arduino project demonstrates creating sound using a buzzer connected to the Arduino board. The buzzer will produce sound with intervals of five seconds.

## Installation

1. Clone this repository to your local machine using `git clone https://github.com/shivaganesht/Arduino-Buzzer-Sound-Code.git`
2. Open the project in the Arduino IDE.

## Usage
![Buzzer](https://github.com/shivaganesht/Arduino-Buzzer-Sound-Code/assets/69391183/60d64ae9-d4b4-43b8-9993-b4109c81e780)

1. Connect your Arduino board to your computer.
2. Upload the code to your Arduino board.
3. The buzzer connected to the built-in pin on the Arduino board will produce sound with intervals of five seconds.

## Code Overview

```cpp
void setup()
{
    pinMode(LED_BUILTIN, OUTPUT); // Set the built-in Buzzer pin as an output
}

void loop()
{
    digitalWrite(LED_BUILTIN, HIGH); // Turn the Buzzer Sound on
    delay(5000); // Wait for five seconds
    digitalWrite(LED_BUILTIN, LOW); // Turn the Buzzer Sound off
    delay(5000); // Wait for five seconds
}
```

If you want to change the duration of the sound intervals, you can modify the delay time in the code. The timing in the delay function is in milliseconds (i.e., 1 second = 1000 milliseconds).

## Conclusion

This project provides a simple example of generating sound using a buzzer with Arduino. Feel free to modify the code to customize the sound intervals according to your requirements!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
