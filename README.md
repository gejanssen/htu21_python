# HTU 21
How to read HTU 21 with python

## Enable I2c for pi

## Connect htu21

<img src="https://github.com/gejanssen/htu21_python/blob/master/htu21.png" align="right" />




## Enable I2C 
```
gej@rpi-b ~/htu21 $ sudo raspi-config nonint do_i2c 0
```

## Enable user-i2c

En de rechten uitdelen

```
gej@rpi-b ~/htu21 $ sudo usermod -aG i2c yourusername
```

###Use :

```
gej@rpi-b ~/htu21 $ python readhtu21.py 
Temp: 19.96  C
Humid: 43.70  %rH
gej@rpi-b ~/htu21 $ 
```

