# stm32-pressure-sensor
Using crystal oscillators to obtain cheaper and high performance sensors than MEMS based pressure sensors.
My position in the project is to recognize the sensor made and to make its output meaningful by using arm-based microcontrollers.
How to works code..
This sensor generates square wave two output point. I did catch thist toogle point with external interrupt and calculated how much time passes between the two wave.
When time is increased We can say pressure is high , when time is reduced We can say pressure is low.

For the accuracy of the results, we increased the ''sample space"" and used the sigma delta method when averaging.
