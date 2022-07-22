<table align="center" border="1" cellpadding="1" cellspacing="1">
	<caption>Deployment Methods</caption>
	<thead>
		<tr>
			<th scope="col">Tools/Algorithm</th>
			<th scope="col">Supported Serialization</th>
			<th scope="col">Deployment Method</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="text-align:center">scikit-learn</td>
			<td style="text-align:center">pickle</td>
			<td style="text-align:center">python, flask, spark scikit</td>
		</tr>
		<tr>
			<td style="text-align:center">XGBoost</td>
			<td style="text-align:center">booster, pickle or spark native</td>
			<td style="text-align:center">XGboost4j, flask, custom java, spark</td>
		</tr>
		<tr>
			<td style="text-align:center">spark ml</td>
			<td style="text-align:center">spark&nbsp; native</td>
			<td style="text-align:center">spark, MLFlow</td>
		</tr>
		<tr>
			<td style="text-align:center">Tensorflow</td>
			<td style="text-align:center">protobuf, tf2onnx, tflite</td>
			<td style="text-align:center">flask, TF serving, Java TensorFlow, c++&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center">H2O</td>
			<td style="text-align:center">POJO, MOJO</td>
			<td style="text-align:center">Java, Python, Flask</td>
	</tbody>
</table>