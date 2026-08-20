Components Needed
    ESP32-C3 module
    MPU-6050 (GY-521) sensor
    SG90 180-degree servo motor
    OLED display (SSD1306, 128x64)
    Wiring Diagram
    MPU-6050 to ESP32-C3:
        VCC to 5V
        GND to GND
        SCL to GPIO 20 (SCL)
        SDA to GPIO 21 (SDA)
    SG90 Servo to ESP32-C3:
        VCC (red wire) to 5V
        GND (brown wire) to GND
        Signal (orange wire) to GPIO 18 (you can choose another GPIO if needed)
Libraries Needed
    Wire.h: For I2C communication.
    Adafruit_GFX.h and Adafruit_SSD1306.h: For controlling the OLED display.
    Adafruit_MPU6050.h: For interfacing with the MPU-6050.
    ESP32Servo.h: For controlling the SG90 servo motor. (in this case but if you are using ESP8266 then Servo.h library will work.
