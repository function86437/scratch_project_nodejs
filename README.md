This is a project rewrite in nodejs. Source is from https://github.com/SarahYuHanCheng/scratch_project

# Installation

## tools
### software
<ul>
	<li><a href="https://nodejs.org/en/">nodejs</a></li>
	<li><a href="http://s4a.cat/#downloads">S4A</a></li>
	<li><a href="https://www.arduino.cc/en/Main/Software">Arduino</a></li>
	<li><a href="">arduino uno</a></li>
</ul>

### harwardware

<ul>
	<li><a href="https://www.arduino.cc/en/Main/ArduinoBoardUno">arduino uno</a></li>
	<li><a href="https://wiki.wemos.cc/products:d1:d1_mini">Wemos D1 mini</a></li>
</ul>

## step by step

<ol>
	<li>Burn uno.ino to your uno board by using aduino IDE</li>
	<li>Prepare more than two Wemos-D1-mini. Burn wifionuno.ino to one of Wemos-D1-mini, and burn Client.ino to others</li>
	<li>Setup environment of nodejs by <a href="https://nodejs.org/en/download/">tutorial</a></li>
	
</ol>

# Start
<ol>
	<li>Connect Wemos-D1-mini(wifionuno) to UNO board <code>Uno -> D1-mini<br> 
								 3  ->   tx   <br>
								 2  ->   rx   <br>
								 5v ->   5v   <br>
								 GND->   G</code></li>
	<li>Let Scratch listen on UNO. Simulate button pressed by connecting D2 and G on D1-mini</li>

</ol>
