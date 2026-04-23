# Sensor Fusion Station — Raspberry Pi Pico

Multi-sensor fusion station with BMP180, IMU (GY-85), 
QMC5883P compass, NEO-6M GPS and OLED display.

## Hardware
- Raspberry Pi Pico (RP2040)
- BMP180 — temperature & pressure
- GY-85/HW-579 IMU — accelerometer + gyroscope  
- GY-271 QMC5883P — magnetometer
- NEO-6M GPS module
- SSD1306 0.96" OLED display

## Wiring
- I2C: GP4 (SDA) / GP5 (SCL)
- GPS UART: GP0 (TX) / GP1 (RX)
- Button: GP14

## Libraries
- Adafruit BMP085
- Adafruit ADXL345
- Adafruit SSD1306
- TinyGPS++
- qmc5883p
