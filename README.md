# TMP100_T.I._temp_sensor
C Application that reads the temperature from T.I TMP100 temperature sensor using i2c communication  

An example on how to call the application from command line:
$ ./tmp100_i2c -A 73 -C 124 -L 0000 -H 65500
Output of application call:
The selected chip-address is: 73
The CONFIG_REGISTER value is: 124
The TEMP_LOW_REGISTER value is: 0000
The TEMP_HIGH_REGISTER value is: 65500
The value stored in the parameters: 0x49 0x7c 0000 0xffdc !
