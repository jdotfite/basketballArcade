# Arcade-Style Arduino Basketball
<img src="https://i.imgur.com/hcS3pOc.jpg" title="Basketball Arduino" />

# Hardware
<ol>
  <li><a href="https://www.adafruit.com/products/2341">Adafruit Audio FX Mini Sound Board - WAV/OGG Trigger - 16MB Flash</a></li>
  <li><a href="https://www.adafruit.com/product/1911">Quad Alphanumeric Display - Red 0.54" Digits w/ I2C Backpack</a></li>
  <li><a href="https://www.adafruit.com/product/1268">Adafruit 1.2" 4-Digit 7-Segment Display w/I2C Backpack - Green</a></li>
  <li><a href="https://www.adafruit.com/product/1927">Sharp GP2Y0D810Z0F Digital Distance Sensor with Pololu Carrier - GP2Y0D810Z0F</a></li>
  <li><a href="https://www.adafruit.com/product/1739">Large Enclosed Piezo Element w/Wires</a></li>
  
</ol>
 
# Scenario detection
<ul>
  <li>Ball hitting backboard (peizo sensor on backboard)</li>
  <li>Ball through hoop (distance sensor near rim)</li>
  <li>Ball hitting backboard AND ball through hoop</li>
  <li>Ball hitting backboard AND NOT ball through hoop</li>
  <li>Air ball over backboard (distance sensor behind backboard facing up)</li>
</ul> 

# Features
<ul>
  <li>Shots made counter</li>
  <li>Shot clock arcade mode</li>
  <li>Sound effects based on scenarios</li>
  <li>Visual effects based on scanarios</li>
</ul>

# Scenario - possible later enhancements
<ul>
  <li>Slam Dunk (flex sensor on rim)</li>
  <li>Ball through hoop AND NOT hitting backboard (distance sensor detection, but peizo sensor not triggered)</li>
</ul>

# Shot clock arcade mode
<ul>
  <li>mode begins via momentary button</li>
  <li>Green numeric display writes 0000</li>
  <li>Red numeric display counts down 3..2..1</li>
  <li>Audio fx chip plays 3...2...1 countdown track</li>
  <li>Red numeric display starts 60 sec countdown</li>
  <li>Audio fx chip plays stressful background sound</li>
  <li>Audio fx chip plays sounds based on sensor feedback while background sound is playing (2 sounds at once possible?)</li>
  <li>Leds show visual feedback (colors change as time is running out?)
  <li>Red numeric display stops at 0 when time is up</li>
  <li>Green numbric display flashes final score when time is up</li>
  <li>buzzer sound effect goes off when time is up</li>
</ul>
