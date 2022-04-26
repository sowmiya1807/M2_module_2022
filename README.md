<h1>THERMAL CONTROL SYSTEM</h1>

<h2>INTRODUCTION:</h2>

A Thermal control system is basically used to control the temperature anywhere like in a car, bus, livingroom, bedroom etc. so, let's take a car as an example in this projec,When a user or driver of the car gets settled on a car, the button sensor will get activated. After that, the user will get access to turn on the heater. The temperature sensor will keep monitoring the temperature and sends the analog value to the microcontroller. The microcontroller then process the analog input of the temperature sensor and sends produces as a temperature value through the  serial communication. 


<h2>SALIENT FEATURES:</h2>

* Flexible approach system
* Driver and passengers can easily adjust the temperature insidd the vehicle
* This application is bet suitable for countries having temperatute less than 0℃.
* This system is user friendly and cost effective.

<h2>CONDITIONS:</h2>

</head>
<body>
	<table>
		<thead>
			<tr>
				<th>ADC Value<br>(Temperature Sensor)</th>
				<th>Output PWM</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;0 - 200</td>
				<td>20% - 20℃&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;210 - 500</td>
				<td>&nbsp;40% - 25℃</td>
			</tr>
			<tr>
				<td>&nbsp;510 - 700</td>
				<td>70% - 29℃&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;710&nbsp; - 1024</td>
				<td>95% - 33℃&nbsp;</td>
			</tr>
		</tbody>
	</table>
  
<h2>SWOT ANALYSIS:</h2>
  
  ![swot](https://user-images.githubusercontent.com/101571637/164236928-1061984c-f087-4a73-8917-b7904645e2d2.jpg)

  
  <h1>4W's AND 1H:</h1>
  
<h2>WHO:</h2>
  For every user who wants high temperature in low temperatutre region can be identified.
  
<h2>WHAT:</h2> 
  This is an application where one can adjust their required temperature to get comfort from the external environmental temperatures.
  
<h2>WHEN:</h2>
  This is used mostly in winter seasons.
  
<h2>WHERE:</h2>
  This application can be implemented in low twmpwrature regions.
  
<h2>HOW:</h2>
  This application is implemented in SimulIDE using Visual Studio code.
	
	
	
	
	
<H2>HIGH LEVEL REQUIREMENTS:</H2>
	

</head>
<body>
	<table>
		<thead>
			<tr>
				<th>REQUIREMENTS</th>
				<th>DESCRIPTION</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;HLR_1</td>
				<td>Microcintroller&nbsp;</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;HLR_2</span>&nbsp;</td>
				<td>Temperature Sensor&nbsp;</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;HLR_3</span>&nbsp;</td>
				<td>&nbsp;LCD or LED Display</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;HLR_4</span></td>
				<td>&nbsp;Temperature Generation</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;HLR_5</span></td>
				<td>Appropriate Software for implementation&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>	





<H2>LOW LEVEL REQUIREMENTS:</H2>



</head>
<body>
	<table>
		<thead>
			<tr>
				<th>REQUIREMENTS</th>
				<th>DESCRIPTION</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;LLR1_1</td>
				<td>ATmega 328 microcontroller</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;LLR2_1</span>&nbsp;</td>
				<td>LM35 and ADC&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;LLR2_2</td>
				<td>ADC with PWM&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;LLR3_1</td>
				<td>LCD or LED Displays&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;LLR4_1</td>
				<td>Heat Pump Module&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;LLR5_1</td>
				<td>VS code with AVR and GCC Compiler&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;LLR5_2</td>
				<td>SimulIDE&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>
