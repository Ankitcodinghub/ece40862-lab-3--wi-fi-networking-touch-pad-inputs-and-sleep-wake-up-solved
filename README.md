# ece40862-lab-3--wi-fi-networking-touch-pad-inputs-and-sleep-wake-up-solved
**TO GET THIS SOLUTION VISIT:** [ECE40862 Lab 3 –Wi-Fi Networking, Touch Pad Inputs, and Sleep/Wake-Up Solved](https://www.ankitcodinghub.com/product/ece40862-lab-3-wi-fi-networking-touch-pad-inputs-and-sleep-wake-up-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94434&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE40862 Lab 3 –Wi-Fi Networking, Touch Pad Inputs, and Sleep\/Wake-Up Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

1. Overview

This assignment deals with connecting your ESP32 board to the Internet over WiFi and exploring sleep modes and wake up sources in the ESP32. You will also be using the RTC module and the on-board touch sensor in this lab. The hardware and software implementation details for this assignment are described in the following sections.

2. Programming Exercise

2.1. Hardware Interfacing

Interface the following components to the board:

<ul>
<li>Two external LEDs (red and green) as GPIO outputs.
o TheredLEDshouldindicateiftheboardisawake(ON)orinsleepmode(OFF).

o The green LED should be controlled by touch-based input (see Table 1).
</li>
<li>One external push button as a GPIO input to use as a wake-up source.</li>
<li>One external Male-Male jumper wire connected to a Touch-enabled pin. Insert the wire into the header on the board. This page gives information about the Touch-enabled pins: http://docs.micropython.org/en/latest/esp32/quickref.html#capacitive-touch. You can select any of the 10 capacitive-touch enabled pins on the board with the following caveat. The pins indicated on the webpage above are for the ESP32 microcontroller itself. On your board however, only 6 out of the 10 touch-enabled pins are available for use. You can figure out the 6 pins by trial and error (HINT: you will get a ‘ValueError’ if you try to assign an unavailable pin as a TouchPad input).
2.2. Software Implementation (main.py)

Your program should implement the following functionality.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2.2.1.Connect to the Internet over WiFi

<ul>
<li>The program should use the network module in MicroPython to connect your ESP32 to a WiFi network using the ‘SSID’ and ‘Password’ for that network. You can create a WiFi hotspot on your mobile/laptop and connect your ESP32 to the hotspot. Refer to the example given in the MicroPython documentation for the network module [1]
NOTE: You can also connect to any other WiFi network which works directly with an SSID and password. However, be aware that enterprise networks such as PAL3.0 which require SSID, username, password, certificates, etc., are unfortunately not supported in Micro Python.
</li>
<li>Each time the board successfully connects to Wi-Fi, the program should print the SSID it has connected to and the interface’s IP address.
Connected to Lenovo-SSID IP Address: 192.168.0.107

2.2.2. Display Current Date and Time using Network Time Protocol (NTP)
</li>
</ul>
<ul>
<li>Get the current time from the Internet using NTP. The program should fetch the current date and time from the NTP server ‘pool.ntp.org’ and use it to set the RTC (real time clock). HINT: check module ntptime. Then, manually adjust the RTC to convert UTC (Coordinated Universal Time) to the current local time zone in West Lafayette.</li>
<li>Similar to lab 2, initialize a hardware timer and display the current date &amp; time every 15 seconds. Do not use time.sleep(). Instead, use the RTC and Timer interrupt/callback like you did in Lab 2. Format the date and time as shown in the example below:
<pre>   Date: 09/29/2021
   Time: 10:00:00 HRS
</pre>
2.2.3. Green LED Control by Touch Input
</li>
</ul>
<ul>
<li>Initialize the Touchpad-enabled pin connected to the jumper wire and calibrate it by observing how the touchpad pin values change when you physically touch the jumper wire.</li>
<li>Initialize a second hardware timer and read the touch pin values every 50 milliseconds using a Timer interrupt/callback and implement the following pattern. Use calibrated values to detect whether the wire is touched or not.
o Touch Pin not touched: Green Led should be OFF

o Touch Pin touched: Green Led should be ON

2.2.4. Red LED, Deep Sleep and Different Wake Up Sources
</li>
</ul>
• The red LED should be ON whenever the ESP32 is awake and OFF when it is in sleep mode.

</div>
</div>
<div class="layoutArea">
<div class="column">
e.g., if your mobile hotspot has an SSID: ‘Lenovo-SSID’ and Password: ‘12345678’, then

</div>
</div>
<div class="layoutArea">
<div class="column">
use this SSID and password for connecting the ESP32 to the Internet.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Use a third hardware timer to put the ESP32 into deep sleep every 30 seconds for a duration of 1 minute. Print out a message on the terminal before going to sleep like:
I am going to sleep for 1 minute.

AWAKE duration: 30 seconds (this will be the duration of the third hardware timer) SLEEP duration: 1 minute (do not need a timer for this, check this link for details on deep

sleep: https://docs.micropython.org/en/latest/esp32/quickref.html#deep-sleep-mode)
</li>
<li>You will be using two different sources of waking up from deep sleep. Your program
should check for both sources and the board should be able to wake up from either source.

2.2.4.1. Wake up Sources

<ul>
<li>Timer Wake Up: Wake up the ESP32 after the predefined sleep duration (1 minute) and print that it’s a timer wake-up.</li>
<li>External Wake Up Mode 0: Configure the switch as an external wake-up source. Pressing the switch within the 1-minute sleep duration should wake up the board and print out it’s an EXT0 wake-up. If one-minute passes and no touch is detected, then your board should wake up due to the Timer Wake Up above.
2.3. Overall Program Flow and Sample Output

The board is powered on for the first time. It connects to the Wi-Fi network, fetches the current time from NTP server, displays them after 15s, and turns on the green led whenever the touch pin wire is touched. It again displays the date and time at 30s and then goes to deep sleep. The program now checks for the push button wake-up signal. If you press the switch or if 1 minute expires, the board wakes up and starts the overall process again. Table 1 shows the LED status functionality. A sample output is also provided here for your understanding. For this sample, we assume that the program started at 10:00:00 hrs. EST.
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1. Sleep and Wake Up Program Flow

</div>
</div>
<div class="layoutArea">
<div class="column">
Mode

Sleep

Sleep

Awake Awake

</div>
<div class="column">
Touch Pin

Not Pressed: No Effect Pressed: No Effect

Not Pressed: Green LED off Pressed: Green LED on

</div>
<div class="column">
Switch

Not Pressed: No Effect Pressed: Wake-Up Not Pressed: No Effect Pressed: No Effect

</div>
<div class="column">
Red Led

Off Off On On

</div>
<div class="column">
Green Led

Off Off Off On

</div>
</div>
<div class="layoutArea">
<div class="column">
Sample Output

</div>
</div>
<div class="layoutArea">
<div class="column">
I (200) wifi: wifi driver task: 3ffe2c34, prio:23, stack:3584, core=0

</div>
</div>
<div class="layoutArea">
<div class="column">
………

………

………

I (22233) network: CONNECTED

I (22883) event: sta ip: 192.168.0.107, mask: 255.255.255.0, gw: 192.168.0.1 I (22883) network: GOT_IP

Connected to Lenovo-SSID IP Address: 192.168.0.107

</div>
</div>
<div class="layoutArea">
<div class="column">
Wi-Fi connection messages posted by ESP

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<pre> Date: 09/11/2019
 Time: 10:00:15 HRS
</pre>
<pre> Date: 09/11/2019
 Time: 10:00:30 HRS
</pre>
I am going to sleep for 1 minute.

<pre> ets Jun  8 2016 00:22:57
</pre>
rst:0x5 (DEEPSLEEP_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT) configsip: 0, SPIWP:0xee……………

…………………

…………………

I (0) cpu_start: Starting scheduler on APP CPU.

Woke up due to EXT0 wakeup.

I (200) wifi: wifi driver task: 3ffe2c34, prio:23, stack:3584, core=0

<pre> ///continues
</pre>
3

</div>
</div>
</div>
