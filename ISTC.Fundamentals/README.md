<h1> Programming Fundamentals for Beginners </h1>
<h2> Primitive Types and Variables </h2>


<h3>Integral Types Table</h3>
		<div class="table-responsive">
			<table class="table table-striped table-bordered">
				<thead>
					<tr>
						<th>C# Type</th>
						<th>.NET Framework Type</th>
						<th>Size [bytes]</th>
						<th>Size [bits]</th>
						<th>Signed</th>
						<th>Range</th>
						<th>Suffix</th>
						<th>Default</th>
					</tr>
				</thead>
				<tbody class="pfb-consolas">
					<tr>
						<td>byte</td>
						<td>System.Byte</td>
						<td>1</td>
						<td>8</td>
						<td>no</td>
						<td>0 to 255</td>
						<td></td>
						<td>0</td>
					</tr>
					<tr>
						<td>sbyte</td>
						<td>System.SByte</td>
						<td>1</td>
						<td>8</td>
						<td>yes</td>
						<td>-128 to 127</td>
						<td></td>
						<td>0</td>
					</tr>
					<tr>
						<td>char</td>
						<td>System.Char</td>
						<td>2</td>
						<td>16</td>
						<td>no</td>
						<td>U+0000 to U+ffff</td>
						<td></td>
						<td>'\0'</td>
					</tr>
					<tr>
						<td>short</td>
						<td>System.Int16</td>
						<td>2</td>
						<td>16</td>
						<td>yes</td>
						<td>-32,768 to 32,767</td>
						<td></td>
						<td>0</td>
					</tr>
					<tr>
						<td>ushort</td>
						<td>System.UInt16</td>
						<td>2</td>
						<td>16</td>
						<td>no</td>
						<td>0 to 65,535</td>
						<td></td>
						<td>0</td>
					</tr>
					<tr>
						<td>int</td>
						<td>System.Int32</td>
						<td>4</td>
						<td>32</td>
						<td>yes</td>
						<td>-2,147,483,648 to 2,147,483,647</td>
						<td></td>
						<td>0</td>
					</tr>
					<tr>
						<td>uint</td>
						<td>System.UInt32</td>
						<td>4</td>
						<td>32</td>
						<td>no</td>
						<td>0 to 4,294,967,295</td>
						<td>U or u</td>
						<td>0</td>
					</tr>
					<tr>
						<td>long</td>
						<td>System.Int64</td>
						<td>8</td>
						<td>64</td>
						<td>yes</td>
						<td>-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807</td>
						<td>L or l</td>
						<td>0L</td>
					</tr>
					<tr>
						<td>ulong</td>
						<td>System.UInt64</td>
						<td>8</td>
						<td>64</td>
						<td>no</td>
						<td>0 to 18,446,744,073,709,551,615</td>
						<td>UL or ul</td>
						<td>0</td>
					</tr>
				</tbody>
			</table>
		</div>
  <br>
		<h3>Floating-Point Types Table</h3>
		<div class="table-responsive">
			<table class="table table-striped table-bordered">
				<thead>
					<tr>
						<th>C# Type</th>
						<th>.NET Framework Type</th>
						<th>Size [bytes]</th>
						<th>Size [bits]</th>
						<th>Signed</th>
						<th>Range</th>
						<th>Precision</th>
						<th>Suffix</th>
						<th>Default</th>
					</tr>
				</thead>
				<tbody class="pfb-consolas">
					<tr>
						<td>float</td>
						<td>System.Single</td>
						<td>4</td>
						<td>32</td>
						<td>yes</td>
						<td>±1.5e-45 to ±3.4e38</td>
						<td>7 digits</td>
						<td>F or f</td>
						<td>0.0F</td>
					</tr>
					<tr>
						<td>double</td>
						<td>System.Double</td>
						<td>8</td>
						<td>64</td>
						<td>yes</td>
						<td>±5.0e-324 to ±1.7e308</td>
						<td>15-16 digits</td>
						<td>D or d</td>
						<td>0.0D</td>
					</tr>
				</tbody>
			</table>
		</div>
  <br>
		<h3>Decimal Type Table</h3>
		<div class="table-responsive">
			<table class="table table-striped table-bordered">
				<thead>
					<tr>
						<th>C# Type</th>
						<th>.NET Framework Type</th>
						<th>Size [bytes]</th>
						<th>Size [bits]</th>
						<th>Signed</th>
						<th>Range</th>
						<th>Precision</th>
						<th>Suffix</th>
						<th>Default</th>
					</tr>
				</thead>
				<tbody class="pfb-consolas">
					<tr>
						<td>decimal</td>
						<td>System.Decimal</td>
						<td>16</td>
						<td>128</td>
						<td>yes</td>
						<td>±1.0e-28 to ±7.9e28</td>
						<td>28-29 significant digits</td>
						<td>M or m</td>
						<td>0.0M</td>
					</tr>
				</tbody>
			</table>
		</div>

  <br>
		<h3>Boolean Type Table</h3>
		<div class="table-responsive">
			<table class="table table-striped table-bordered">
				<thead>
					<tr>
						<th>C# Type</th>
						<th>.NET Framework Type</th>
						<th>Size [bytes]</th>
						<th>Size [bits]</th>
						<th>Range</th>
						<th>Default</th>
					</tr>
				</thead>
				<tbody class="pfb-consolas">
					<tr>
						<td>bool</td>
						<td>System.Boolean</td>
						<td>1</td>
						<td>8</td>
						<td>true or false</td>
						<td>false</td>
					</tr>
				</tbody>
			</table>
		</div>

