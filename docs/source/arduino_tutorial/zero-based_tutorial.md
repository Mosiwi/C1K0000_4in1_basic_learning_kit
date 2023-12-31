# Arduino_zero-based_tutorial     
-----------------------------
This tutorial only focuses on practical operation, without the need to understand the principles, and understands the simplest Arduino programming operation, so that learners can get a sense of achievement and arouse their interest.    

## Previous preparation       
-----------------------        
1. Install the [**Arduino IDE**](https://docs.mosiwi.com/en/latest/arduino/resources/arduino_ide/arduino_ide.html).  
2. Install the [**Mosiwi basic learning kit**](https://docs.mosiwi.com/en/latest/arduino/A1E0000_basic_learning_shield/A1E0000_basic_learning_shield.html#integration-library) library.    
3. Basic operation of the [**Arduino UNO R3**](https://docs.mosiwi.com/en/latest/arduino/A1D0000_uno_r3/A1D0000_uno_r3.html).    

```{tip}
If you've already done some of the steps above, you don't need to go through the steps you've already done.    
```   

## Chapter1 RGB LED     
-------------------         
Connect control board to your computer with USB cable：    
![Img](../_static/arduino_tutorial/zero-based_img/43img.jpg)

1. Open "2.0.0 RGB led" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/1img.png)    

1. Select motherboard with COM port:    
![Img](../_static/arduino_tutorial/zero-based_img/2img.png)    

1. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/3img.png)    

1. Experimental result:    
![Img](../_static/arduino_tutorial/zero-based_img/4img.png)    
RGB LED lights flash red, green, blue, yellow, cyan, mauve and white.   

## Chapter2 waterfall light   
---------------------------
1. Open "2.1.0_Waterfall_light" Example:   
![Img](../_static/arduino_tutorial/zero-based_img/5img.png)    

2. Select motherboard with COM port:   
![Img](../_static/arduino_tutorial/zero-based_img/6img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/7img.png)   

4. Experimental result:    
![Img](../_static/arduino_tutorial/zero-based_img/8img.png)   
Eight white LED lights turn on and off in a cycle.   

## Chapter3 Led bar   
-------------------
1. Open "2.1.1_Led_strip" Example:   
![Img](../_static/arduino_tutorial/zero-based_img/9img.png)   

2. Select motherboard with COM port:    
![Img](../_static/arduino_tutorial/zero-based_img/10img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/11img.png)    

4. Experimental result:     
![Img](../_static/arduino_tutorial/zero-based_img/12img.png)    
Push up the potentiometer to light more white LED lights, push down the potentiometer to extinguish more white LED lights.    

## Chapter4 music LED   
---------------------
1. Open "2.3.1_Music_LED" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/13img.png)    

2. Select motherboard with COM port:    
![Img](../_static/arduino_tutorial/zero-based_img/14img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/15img.png)    

4. Experimental result:     
![Img](../_static/arduino_tutorial/zero-based_img/16img.png)    
When you sing into a microphone or play music on your device, LED lights pulsate to the rhythm of the song.    

## Chapter5 IR remote   
---------------------
1. Open "2.6.1_IRremote" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/17img.png)     

2. Select motherboard with COM port:     
![Img](../_static/arduino_tutorial/zero-based_img/18img.png)     

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/19img.png)     

4. Experimental result:      
Use the infrared remote control to repeatedly press the "OK" key in front of the infrared receiver on the expansion board to turn on and off the red LED light on the expansion board.     
![Img](../_static/arduino_tutorial/zero-based_img/20img.png)    

```{note}   
Button batteries must be installed when using the infrared remote control. If the infrared remote control has been allocated with button batteries, the separator at the bottom of the remote control must be pulled out.  
```       

## Chapter6 button   
------------------
1. Open "1.1.0_Button" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/21img.png)    

2. Select motherboard with COM port:    
![Img](../_static/arduino_tutorial/zero-based_img/22img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/23img.png)    

4. Experimental result:     
![Img](../_static/arduino_tutorial/zero-based_img/24img.png)    
Press and hold the OK button on the expansion pad to light up the red LED light. Release your hand and turn off the red LED light.      

## Chapter7 digital tube and button (spi)   
-----------------------------------------
1. Open "1.8.0_Digital_tube_Button_spi" Example:     
![Img](../_static/arduino_tutorial/zero-based_img/25img.png)    

2. Select motherboard with COM port:      
![Img](../_static/arduino_tutorial/zero-based_img/26img.png)    

3. Upload code:     
![Img](../_static/arduino_tutorial/zero-based_img/27img.png)    

4. Experimental result:      
![Img](../_static/arduino_tutorial/zero-based_img/28img.png)    
When pressing the <span style="color: rgb(255, 76, 65);">"U"</span> key, the 4-digit digital tube displays "16.0";           
When pressing the <span style="color: rgb(255, 76, 65);">"D"</span> key, the 4-digit digital tube displays "8.0";       
When pressing the <span style="color: rgb(255, 76, 65);">"L"</span> key, the 4-digit digital tube displays "4.0";        
When pressing the <span style="color: rgb(255, 76, 65);">"R"</span> key, the 4-digit digital tube displays "2.0";     
When pressing the <span style="color: rgb(255, 76, 65);">"OK"</span> key, the 4-digit digital tube displays "1.0".       

## Chapter8 thermohygrometer   
----------------------------
1. Open "2.5.0_Thermohygrometer" Example:     
![Img](../_static/arduino_tutorial/zero-based_img/29img.png)    

2. Select motherboard with COM port:      
![Img](../_static/arduino_tutorial/zero-based_img/30img.png)    

3. Upload code:   
![Img](../_static/arduino_tutorial/zero-based_img/31img.png)    

4. Experimental result:    
![Img](../_static/arduino_tutorial/zero-based_img/32img.png)    
The 4-digit digital tube will display the current ambient temperature and humidity in degrees Celsius.    

## Chapter9 thermohygrometer   
----------------------------
1. Open "2.4.2_Thermohygrometer" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/33img.png)    

2. Select motherboard with COM port:    
![Img](../_static/arduino_tutorial/zero-based_img/34img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/35img.png)    

4. Experimental result:     
The current ambient temperature is displayed on a 4-digit digital tube in 3 seconds. The format is xx.xC "z. Temperature data is stored every 0.5 minutes in the eeprom of the expansion board, which is a kind of memory that does not lose power data.    
![Img](../_static/arduino_tutorial/zero-based_img/36img.png)    

Open the serial port monitor as shown in the following figure, press the <span style="color: rgb(255, 76, 65);">"OK"</span> button on the expansion board, and the serial port monitor will print out the temperature data in the eeprom.    
![Img](../_static/arduino_tutorial/zero-based_img/37img.png)    

If you are using an IDE above 2.0, you can also display the data as a temperature graph as follows:    
![Img](../_static/arduino_tutorial/zero-based_img/38img.png)       

```{note}   
After following steps 1 and 2, click the "OK" key on the expansion board, multiple curves will be displayed. Then, select "value 1" according to step 3.   
```    

## Chapter10 jingle bells     
-------------------------
1. Open "2.2.2_Jingle_bells" Example:    
![Img](../_static/arduino_tutorial/zero-based_img/39img.png)    

2. Select motherboard with COM port:   
![Img](../_static/arduino_tutorial/zero-based_img/40img.png)    

3. Upload code:    
![Img](../_static/arduino_tutorial/zero-based_img/41img.png)    

4. Experimental result:     
![Img](../_static/arduino_tutorial/zero-based_img/42img.png)    
The buzzer on the expansion board will play the "Jingle_bells" song all the time.       

--------
**End!**    
For more exciting tutorials, check out the [basic tutorial](./basic_tutorial.md)!    












