# digcom
Matlab app that simulates a digital baseband communication system
![App](https://user-images.githubusercontent.com/61466717/78936272-8dcad580-7aae-11ea-8dba-599824244a80.PNG)


### Included Schemes
app includes **NRZ**,**RZ**,**Manchester**,**AMI**, **Miller**, **MLT3** and **2B1Q**.

### Description
Source input is 10 bits, the pulses are shaped and to simulate the channel, noise is added. 
At the reception we have the reception filter, sampling and decision making. 
the Bit Error Rate (BER) is calculated. all the signals are plotted including the power spectral density.

You can change the SNR and observe how the BER behaves for different schemes.  

### Install
You need to package the app ( .mplab file ) using Matlab App Designer ( a packaged app is included in the **packaged app** folder) and then install it in matlab.
run the app by typing **digcom** in the command prompt.
