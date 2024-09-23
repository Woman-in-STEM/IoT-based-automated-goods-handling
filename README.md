# IoT based automatic handling of goods

Coal India Limited (CIL) has been supplying coal to its consumers by Rail through Railway Sidings. The railway wagons at such sidings are loaded through contractual means by payloader. The loading of wagons by contractual arrangement often results in overloading or underloading Railway wagons. The rules of Penal overloading and underloading are notified by the Railway. Any penalty for overloading charged by the Railway for any consignment is payable by the purchaser. However, in case of underloading of wagons, credit for idle freight is adjusted in coal bills. Thus any idle freight for under-loading is borne by CIL. During 2021-22, the expense for under-loading was nearly Rs.593 Cr. whereas the contract for wagon loading itself was only Rs.276 Cr. 
Hence, a digital solution is proposed in the form of sensor/ IoT to prevent the under-loading and overloading of Railway wagons.             

Key words: Sensor, IOT

<br><hr><br>

## Approach
After the goods are loaded into the wagon, the load and weight sensor is activated. 
For the prototype, the <b>SEN0160</b> module is used, which has a capacity of 1kg. 
The sensor will transmit the data to a high precision A/D converter (Analog to digital converter), namely, the <b>HX711 Weighing Sensor Module</b>, which also acts as an amplifier. 
The output of this device is then sent to the <b>Arduino microcontroller</b>. It will store the ideal capacity of the train wagon as a baseline value.
The detected weight is then compared with this value to determine if the wagon is overloaded or underused. Accordingly, the microcontroller will activate the relevant indicators to let the user know. 
Here, a 16x2 LCD is used to give the state of the wagon: <i>normal, underloaded, or overloaded</i>. 
In addition to this, if the weight exceeds maximum capacity, a buzzer will also sound as a warning. 

<br><hr><br>

## Description of Technology Stack
<ul>
  <li>Software
    <ol>
      <li>Front-end : XML</li>
      <li>Back-end : Java and Python Language</li>
    </ol>
  </li>  
  <li>
    Hardware
    <ol>
      <li>Arduino UNO Board</li>
      <li>Embedded Python</li>
      <li>Components : Sensor, Amplifier, Arduino UNO Board, LCD, LEDs and Bluetooth</li>
    </ol>
</li>  
</ul>

<br><hr><br>

## Use cases of project
<ol>
<li>Improve the transparency in railway department and lowers the maintenance on railway tracks.</li>
<li>Used in various transportation means for example in cargo aircrafts, freighters, trailers, etc.</li>
<li>Used in check posts (toll plaza).</li>
</ol>
