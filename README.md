# HTU 21
How to read HTU 21 with python

Enable user-i2c

```
sudo usermod -aG i2c yourusername
```

Use :

```
gej@rpi-b ~/htu21 $ python readhtu21.py 
Temp: 19.96  C
Humid: 43.70  %rH
gej@rpi-b ~/htu21 $ 
```

