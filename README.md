# DIY Bose SoundTouch - Philips Hue - Amazon Alexa - Smart Home Security System

##### NOTE: 12/29/2017 - This project is in the beginning stages of planning and development.

## Purpose/Vision
The purpose of this project is to create a DIY security system that monitors and alerts for detected movement at certain entry ways
to your home. The project will utilize multiple Raspberry Pis, as well as smart-home products such as Amazon Alexa, Philips Hue Smart Bulbs, and Bose SoundTouch speaker(s). The user will interact with a Java GUI application, on a small touchscreen mounted to the wall. The user may also interact with the security system on an Android application (iOS may be added future state). 

##### Security Modes:
###### Disarmed
- No motion activity recorded
- No alerts
- No images captured

###### Armed: Home
- This mode should be used when the home owner/tenant is home and awake. 
- Motion Detection
- Alexa notifies home owner/tenant by stating "Someone is at the front door!" (Or other location)
- Touch screen display generates live video feed of camera
- Image(s) are captured and saved to NAS server (2nd Raspberry Pi with external hard drive). 

###### Armed: Away
- This mode should be used when no one is home. 
- Motion Detection
- Push Notification is sent to home owner/tenant's mobile device via Android app. 
- Images are captured and saved to NAS server. 
- Images are instantly accessible via mobile Android app. 

###### Armed: Night
- This mode should be used when the home owner/tenant is home and going to sleep. 
- Motion Detection
- Touch screen display generates live video feed of camera
- Bose SoundTouch speakers begin playing loud "Guard Dog Barking" sounds. 
- Phillips Hue lights turn on. 
- Image(s) captured and saved to NAS server
- Disarm button within Mobile app, or touchscreen interface, will turn off Bose SoundTouch audio, and turn off Philips Hue lights. 

## Requirements
###### Required Hardware:
- [Raspberry Pi 3 Model B (x2 minimum)](https://www.adafruit.com/product/3055)
- Micro SD cards with Raspbian OS, and some additional storage space. 
- [Raspberry Pi Power Supply](https://www.adafruit.com/product/1995)
- (Optional) External Hard Drive for additional server storage. I will be using a [WD MyBook 4TB](https://www.wdc.com/products/external-storage/my-book-new.html)
- [PiTFT Touch Screen 320x240](https://www.adafruit.com/product/1601)
- [PIR Motion Sensor](https://www.adafruit.com/product/189)
- [Raspberry Pi Camera](https://www.adafruit.com/product/3099)
- [Raspberry Pi Case and Face Plate for PiTFT](https://www.adafruit.com/product/3062)
- Another case for the 2nd Raspberry Pi (NAS Server). I'm currently using the [Flirc Raspberry Pi Case](https://www.amazon.com/Flirc-Raspberry-Case-Gen2-Model/dp/B07349HT26/ref=sr_1_3?ie=UTF8&qid=1514509745&sr=8-3&keywords=raspberry+pi+flirc+case)
- Amazon Alexa Product. I'll be using an [Echo Dot v2](https://www.amazon.com/Amazon-Echo-Dot-Portable-Bluetooth-Speaker-with-Alexa-Black/dp/B01DFKC2SO/ref=sr_1_1?s=electronics&ie=UTF8&qid=1514509979&sr=1-1&keywords=echo+dot)
- Philips Hue Smart Bulbs. You'll also need the Bridge. I'd recommend this [starter kit](https://www.amazon.com/Philips-Starter-Compatible-HomeKit-Assistant/dp/B07354SP1C/ref=sr_1_2?ie=UTF8&qid=1514510050&sr=8-2&keywords=philips+hues)
- Bose SoundTouch product. I'll be using a [SoundTouch 20](https://www.amazon.com/Bose-SoundTouch-III-Wireless-Speaker/dp/B011IH6E26/ref=sr_1_2?ie=UTF8&qid=1514510114&sr=8-2&keywords=soundtouch+20)
- A computer for coding!

###### Development Requirements:
- Java [JRE](http://www.oracle.com/technetwork/java/javase/downloads/jre9-downloads-3848532.html) and [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html)
- IDE(s). I'll be using [InteliJ IDEA](https://www.jetbrains.com/idea/) for the main application, and [Android Studio](https://developer.android.com/studio/index.html) for the mobile app.
- [Raspbian OS](https://www.raspberrypi.org/downloads/raspbian/)
- APIs:
  - [Bose API](https://developer.bose.com/)
  - [Philips Hue API](https://www.developers.meethue.com/)
  - [Alexa API/Skills](https://developer.amazon.com/docs/alexa-voice-service/api-overview.html)
  
## Instructions
Coming soon! I will be updating as the project progresses! 






