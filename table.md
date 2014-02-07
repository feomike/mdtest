<h3 id="JUDPLATENCY">JUDPLATENCY Reference</h3>
		<table>
			<thead>
				<tr>
					<th>Property</th>
					<th>Type</th>
					<th>Description</th>
					<th>Explanation</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td class="code">type</td>
					<td class="shorter">String</td>
					<td class="shorter">JUDPLATENCY</td>
					<td class="longer">The active metric type 'JUDPLATENCY' describes measurement results of the active test for latency performance.</td>
				</tr>
				<tr>
					<td class="code">datetime</td>
					<td class="shorter">String</td>
					<td class="shorter">Fri Jan 25 15:36:07 GMT 2013</td>
					<td class="longer">The field contains the time test finished
						in UTC.</td>
				</tr>
				<tr>
					<td class="code">lost_packets</td>
					<td class="shorter">Integer</td>
					<td class="shorter">1</td>
					<td class="longer">The field contains the number of lost
						packets during the test</td>
				</tr>
				<tr>
					<td class="code">rtt_avg</td>
					<td class="shorter">Integer</td>
					<td class="shorter">255144</td>
					<td class="longer">The field contains the average RTT in
						microseconds</td>
				</tr>
				<tr>
					<td class="code">rtt_max</td>
					<td class="shorter">Integer</td>
					<td class="shorter">1488525</td>
					<td class="longer">The field contains the maximum RTT in
						microseconds</td>
				</tr>
				<tr>
					<td class="code">rtt_min</td>
					<td class="shorter">Integer</td>
					<td class="shorter">68023</td>
					<td class="longer">The field contains the minimum RTT in
						microseconds</td>
				</tr>
				<tr>
					<td class="code">rtt_stddev</td>
					<td class="shorter">Integer</td>
					<td class="shorter">243171</td>
					<td class="longer">The field contains the standard deviation
						RTT measured in microseconds</td>
				</tr>
				<tr>
					<td class="code">success</td>
					<td class="shorter">Boolean</td>
					<td class="shorter">true</td>
					<td class="longer">The field contains the number of successes
						(note: use failures/(successes+failures)) for packet loss)</td>
				</tr>
				<tr>
					<td class="code">target</td>
					<td class="shorter">String</td>
					<td class="shorter">n1-the1.samknows.com</td>
					<td class="longer">The field holds a string of the measurement
						server target hostname or IP address. The value is pulled from the
						test configuration file.</td>
				</tr>
				<tr>
					<td class="code">target_ipaddress</td>
					<td class="shorter">String</td>
					<td class="shorter">46.17.56.234</td>
					<td class="longer">The field holds a four tuple colon
						deliminated IP address of the 'target' measurement server, as
						resolved by the handset's locally configured DNS for the active
						network used to execute the test.</td>
				</tr>
				<tr>
					<td class="code">timestamp</td>
					<td class="shorter">Integer</td>
					<td class="shorter">1359128167</td>
					<td class="longer">The field contains the time the measurement
						concluded represented as a sql TIMESTAMP datatype.
						http://developer.android.com/reference/java/sql/Timestamp.html</td>
				</tr>
			</tbody>
		</table>
