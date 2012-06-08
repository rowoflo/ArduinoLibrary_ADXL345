ADXL345 Project

DESCRIPTION:
    This class is used to interface the Arduino with the ADXL345 digital 
    accelerometer pressure sensor.
 
USAGE:
    The pressure sensor only needs 5 pins hooked up to use: 3.3V (VCC, CS), 
    GND, I2C (SDA, SCL).
    
    See ADXL345.h header file for class information.

NOTES:
    If running on an Arduino that operates at 5V (e.g. UNO) it is recommended
    to use a logic level converter for the I2C interface because the sensor
    runs at 3.3V. However, it has been found that the sensor operates normally
    if it is hooked up directly to the Arduino.
 
EXAMPLES:

VERSIONS:
    0.0 - Initially created by bildr.org
        Initially created.

    1.0 - 12/18/11 - Rowland O'Flaherty (rowlandoflaherty.com)
        My initial release with modifications.
    