# Temperature-Controlled-DC-Fan

# Abstract :
      ~ Generally, electronic devices produce more heat.
      So this heat should be reduced in order to protect the device.
      
      ~ The aim of this project is to design a Temperature Controlled DC Fan
      which automatically turns on a DC Fan when the temperature increases above
      a certain limit and also the temperature limit can be changed anytime using input from UART.
      
If the temperature exceeds 35 degree Celsius -> The microcontroller will turn on the relay.
(ambient temperature limit of laptop)            Now, 12V DC source is connected which starts the fan.

If the temperature drops below 35 degree Celsius -> The microcontroller will turn off the relay ,
                                                    but the fan speed will slow down gradually
                                                    which further reduces the temperature.
                                                    
# Components used :
      ~ LPC2148 Microcontroller
      ~ LM35(Temperature Sensor) 
      ~ Single Pole Double throw(SPDT) Relay
      ~ 12V DC Fan
      ~ Virtual terminal
      ~ LM016L (16 X 2 LCD Display)
      ~ Push Button     
