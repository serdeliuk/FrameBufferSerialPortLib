### FrameBufferSerialPortLib
EDK2 port FrameBufferSerialPortLib


[![download](https://img.shields.io/github/downloads/serdeliuk/FrameBufferSerialPortLib/total)](https://github.com/serdeliuk/FrameBufferSerialPortLib/releases/download/2/FrameBufferSerialPortLib.2.zip)

- Please replace in `FrameBufferSerialPortLib.c` DELAY variable value with your own prefered value in microseconds
<br>Default value is 0.2s

`UINTN delay = 200000; // 0.2s`
<br> Below are few examples on how to set the delay value
```
1000000 = 1s
 500000 = 0.5s
 100000 = 0.1s
      0 = disable delay
```

You can change the color of the text output to GREEN or red using following escape chars

` \v for GREEN \v` v for victory <br>
` \a for RED \a` a for alert 

I hope that will help in your future projects<br><br>
Have fun!

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/serdeliuk) any donation is highly appreciated!

NOTE: if you know who initially build this library please let me know to add a credentials list here, many thanks
