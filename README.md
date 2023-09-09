Agree it!!! It has happened to all of us. Many times we misplace our keys and go searching for them everywhere in the house, and after a long search, we end up finding them with much distress. Now, the obvious solution here is to place your keys in their right place, but as engineers, what’s the fun in doing that. So, in this tutorial, we are going to build a simple IoT-based Smart Key Chain just using ESP8266-01, Buzzer, and Battery. Now in case if you can’t find your keys and you remember that you have attached an IoT keychain to your keys, so you take out your phone and open Chrome and open your Keychain Webpage. Then you click on the toggle button, and in moments, you hear a beep sound coming from your keychain and with this, you can easily track your keys.
This is the perfect project for those who frequently place their keys here and there and are unable to find it when needed the most. So here I bring Smart Keychain, a smart companion for your keys. No worries where are keys are just take out your smart phone and give a trigger to your keys, they will automatically says where they are. I made this project using ESP8266 12E development board. Lets see how to make it...
Step 1: Components Required
You will require the following components to make a Smart Keychain.
->General Purpose PCB
->Female Bug strip
->Esp8266 12E dev board
->A buzzer
->Battery
Step 2: Connections
Just connect Buzzer to D0 pin of ESp8266 dev board. Here D0 pin is nothing but the built in LED pin. Connect negative terminal to D0 pin and positive terminal of buzzer to 3.3V. Thats it, this are the only connection you need to make for your smart keychain.
Step 3: Programming
I have done the programming of Smart Keychain in Arduino. Program is very simple, I have just edited the example code of Telnet to Serial for Esp8266.
So I have programmed it in such a way that, It will get automatically connected to the wifi router or hotspot whose ssid name and password we have already entered in the code. After that it will wait for data from our smart phone. So In our smart phone we will open Telnet app, connet to the local IP of our module at port 23 and will send any random data, the keychain will start ringing.
And this is how we can easily find our keys. This is just like we find our phone,if it is misplaced, by simply calling to our number. So this is simple yet most useful project.
We can make this keychain even thinner by replacing 9V battery with 3.3V LiPo batteries. Hence with this its size will really reduced to great extent.
