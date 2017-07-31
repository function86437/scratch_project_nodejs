This is a project rewrite in nodejs. Source is from https://github.com/SarahYuHanCheng/scratch_project

# Installation

* [Multi-WiFiS4A使用說明](goo.gl/t2iEq3)
* [安裝教學](https://hackmd.io/s/SyjIY4ZVZ)
* [安裝截圖說明](https://hackmd.io/s/B1bSCBzUb)

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

## Problem with Arduino IDE and Wemos-D1-mini
<ul>
	<li>Q1: I can't find Wemos-D1-mini in Arduino IDE(Tools > Board)? </li>
		<p>You have to add this url <code>http://arduino.esp8266.com/stable/package_esp8266com_index.json</code> in Arduino > Perferences > Additional Boards Manager URLs, then update the board firmware using board manager(path: Tools > Board > Board Manager > search for ESP266 > install > Done  </p>
</ul>

## step by step

<ol>
	<li>Burn uno.ino to your uno board by using aduino IDE</li>
	<li>Prepare more than two Wemos-D1-mini. Burn wifionuno.ino to one of Wemos-D1-mini, and burn Client.ino to others</li>
	<li>Setup environment of nodejs by <a href="https://nodejs.org/en/download/">tutorial</a></li>
	
</ol>

# Start
<ol>
	<li>Connect Wemos-D1-mini(wifionuno) to UNO board(pin by pin)</li><br><code>Uno -> D1-mini</code><br> 
								 <code>3  ->   tx  </code> <br>
								 <code>2  ->   rx  </code> <br>
								 <code>5v ->   5v  </code> <br>
								 <code>GND->   G</code>
	<br>							 
	<li>Import project in Scratch and then press green flagto start the stage.</li>
	<li>Let Scratch listen on UNO. Simulate button pressed by connecting pin of D2 and GND on D1-mini</li>

</ol>



# 安裝

## 工具
### 軟體

<ul>
	<li><a href="https://nodejs.org/en/">nodejs</a></li>
	<li><a href="http://s4a.cat/#downloads">S4A</a></li>
	<li><a href="https://www.arduino.cc/en/Main/Software">Arduino</a></li>
	<li><a href="">arduino uno</a></li>
</ul>

### 硬體

<ul>
	<li><a href="https://www.arduino.cc/en/Main/ArduinoBoardUno">arduino uno</a></li>
	<li><a href="https://wiki.wemos.cc/products:d1:d1_mini">Wemos D1 mini</a></li>
</ul>

## Arduino IDE 與 Wemos-D1-mini 的問題

<ul>
	<li>我不能在Arduino編輯軟體的裝置中找到Wemos-D1-mini?(工具>主板)</li>
	<p>加入這行 <code>https://arduino.esp8266.com/stable/package_esp8266com_index.json</code>到路徑：Arduino>屬性>新增主板管理員,並到路徑：工具>主板>主板管理員>搜尋ESP8266>安裝>完成
</p>
</ul>

## 步驟

<ol>
	<li>使用Arduino 編輯程式燒錄 uno.ino 檔案到你的UNO 主板中</li>
	<li>準備兩塊以上的Wemos-D1-mini,其中一塊燒錄wifionuno.ino檔案,剩下的都燒錄Client.ino檔案</li>
	<li>設定nodejs的環境,按照官方<a href="https://nodehs.org/en/download/">教學</li>
</ol>

# 開始

<ol>
	<li>連接Wemos-D1-mini(wifionuno)到UNO主板(依照以下接腳)</li><br> <code>UNO -> D1-mini</code><br>
								 <code>3  ->   tx  </code> <br>
								 <code>2  ->   rx  </code> <br>
								 <code>5v ->   5v  </code> <br>
								 <code>GND->   G   </code> 
	<br>
	<li>匯入Scratch專案並按綠旗開始專案</li>
</ol>
