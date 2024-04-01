**ABOUT**
While I was thinking of what to make for this project, I went through some ideas like Obstacle Avoidance, using ultra-sound sensors for a radar system, etc. Then I thought of my iPhone telling where my AirPods are in a room by pointing at the direction it is in, taking this as inspiration I thought of how I could recreate that using an Arduino, but then found out that the Bluetooth interphases that are available for the Arduino are only viable if the distance is above a meter, then I thought of how I could use a microphone instead to track a certain frequency. Thus this bot is created.

**This bot uses Fourier transforms to convert the samples collected from the microphone to the frequency spectrum. After which we figure out which microphone has the highest amount of that frequency and the motors do the rest of the work of taking the bot towards it.**

**This code is by no means perfect, you can tweak it to make it more optimized, be it the Fourier transform, or the motor control. This is a basic code that explores the concept of frequency following as I could not find any resource for it online, I hope to make significant updates to this code in the future :)**
![image](https://github.com/unrav04/VIRENthebot/assets/160302540/afddf3da-dbbd-4ccb-93d2-b14a89069875)
![image](https://github.com/unrav04/VIRENthebot/assets/160302540/caf49db2-f0ba-4017-88bb-a18cd92cf4f2)
