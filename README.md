# Wifi-Controlled-RC-Car

## Requirements

➢ NodeMCU ESP8266 micro-controller <br>
➢ BTS7960B Motor Driver ( x 2 ) <br>
➢ 12-24V DC Motors ( x 4 ) <br>
➢ Jumper wires <br>
➢ Powersupply according to Motors <br>
➢ 5V power supply for ESP8266 and BTS7960B <br>


## Additional Board Manager URL for NodeMCU ESP8266

<pre>http://arduino.esp8266.com/stable/package_esp8266com_index.json</pre>

## Default Wifi Station credentials of NodeMCU :

SSID : RC_PowerCAR <br>
Password : connect_me <br>

<h2 align="center"> <a
        href="https://play.google.com/store/apps/details?id=com.bluino.esp8266wifirobotcar&hl=en_US&gl=US">Android
        app</a> to control
    the car </h2>

<br>

## Pin Diagram

<table>
    <thead>
        <tr>
            <th style="text-align:center">NodeMCU</th>
            <th style="text-align:center">BTS7960B</th>
            <th style="text-align:center">Details</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:center"><strong>D3</strong> (Optional)</td>
            <td style="text-align:center"><strong>R_IS &amp; L_IS (Both Drivers)</strong></td>
            <td style="text-align:center">Side Current Output (Active Low) </td>
        </tr>
        <tr>
            <td style="text-align:center"><strong>D4</strong> (Required)</td>
            <td style="text-align:center"><strong>R_EN &amp; L_EN (Both Drivers)</strong></td>
            <td style="text-align:center">Rotation Enable Pins (Active High) </td>
        </tr>
        <tr>
            <td style="text-align:center"><strong>D5</strong> (Required)</td>
            <td style="text-align:center"><strong>LPWM (1st BTS7960B)</strong></td>
            <td style="text-align:center">1st BTS7960B Forward Rotation PWM</td>
        </tr>
        <tr>
            <td style="text-align:center"><strong>D6</strong> (Required)</td>
            <td style="text-align:center"><strong>RPWM (1st BTS7960B)</strong></td>
            <td style="text-align:center">1st BTS7960B Reverse Rotation PWM</td>
        </tr>
        <tr>
            <td style="text-align:center"><strong>D7</strong> (Required)</td>
            <td style="text-align:center"><strong>LPWM (2nd BTS7960B)</strong></td>
            <td style="text-align:center">2nd BTS7960B Forward Rotation PWM</td>
        </tr>
        <tr>
            <td style="text-align:center"><strong>D8</strong> (Required)</td>
            <td style="text-align:center"><strong>RPWM (2nd BTS7960B)</strong></td>
            <td style="text-align:center">2nd BTS7960B Reverse Rotation PWM</td>
        </tr>
    </tbody>
</table>
