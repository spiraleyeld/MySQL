## Set up MySQL on Mac
https://spiraleyeld.gitbooks.io/awei_wd/content/dan-yuan-mysql.html


<table style="border:3px #cccccc solid;" cellpadding="10" border='1'>
	<thead>
		<tr>
			<td>A</td>
			<td>B</td>
			<td>C</td>
			<td>D</td>
			<td>E</td>
			<td>F</td>
		</tr>
	</thead>
	<tbody> <!--- [  [{"AA":5},{"EE":5},{"BB":3},{"CC":2}], [{"BB":2}],[{"AA":3},{"EE":3},{"BB":2}]  ]  --->
		<tr> <!--- [5,5,3,2] --->
			<td rowspan="5">AA</td>
			<td rowspan="3">BB</td>
			<td rowspan="2">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="5">EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr>
			<td rowspan="5" hidden>AA</td>
			<td rowspan="3" hidden>BB</td>
			<td rowspan="2" hidden>CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="5" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr>
			<td rowspan="5" hidden>AA</td>
			<td rowspan="3" hidden>BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="5" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr> <!--- [2] --->
			<td rowspan="5" hidden>AA</td>
			<td rowspan="2">BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="5" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr>  
			<td rowspan="5" hidden>AA</td>
			<td rowspan="1" hidden>BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="5" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr> <!--- [3,2,3] --->
			<td rowspan="3">AA</td>
			<td rowspan="2">BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="3">EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr>
			<td rowspan="3" hidden>AA</td>
			<td rowspan="2" hidden>BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="3" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
		<tr>
			<td rowspan="3" hidden>AA</td>
			<td rowspan="1" hidden>BB</td>
			<td rowspan="1">BB</td>
			<td rowspan="1">CC</td>
			<td rowspan="1">DD</td>
			<td rowspan="3" hidden>EE</td>
			<td rowspan="1">FF</td>
		</tr>
	</tbody>
</table>
