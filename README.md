# NOAA_ImgDecoder



## APT Signals

APT signal is an analogically method to transmit images. It is used by some satellites which are pretty often used by radio amateur such as NOAA 15, 18 and 19. The main challenge to build this program was to find documentation to understand how to decode APT signals. 

## Application Description

The program is extremely simple, you just have to use an audio wav file  (recorded at 11025 sample/s if possible) and to press the button "Decode". Processing time might last several seconds or even several minute (depending on you computer and the file length). I included a wav file in the folder as example (still from google). You can save the image as bmp by pressing "Save image", you will find it in the folder of the app, or in the same folder with the source code.

![App preview](https://ni.i.lithium.com/t5/image/serverpage/image-id/239244i7E179EF3C65A9619/image-size/large?v=1.0&px=999)

 As long as it is a first version, it will be buggy and it will requires a lot of improvement. The code is free (use with your LabVIEW License).

Don't hesitate to give me your feedback, I will be very glad to hear it!

