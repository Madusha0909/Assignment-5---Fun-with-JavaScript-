# Assignment-5-Fun-with-JavaScript
<!DOCTYPE html>
<html>
	<head>
		<title>Fancify Shamcify</title>
		<!-- link to your script file here -->
		<script src = "fancifymytext.js"> </script>	
	</head>
	<body>
		<h1>Fancify my Text</h1>

		<!-- Your UI controls go here -->
		<fieldset>
			<legend> Text </legend>
			<textarea id="txt" rows="4" cols="30"></textarea>
		</fieldset>
		<fieldset>
			<legend> Fancify </legend>
			<button onclick="bigger()"> Bigger! </button> <br>
			<input type = "radio" name="style" id="fancy" onchange="fancy()"> FancyShmancy <br>
			<input type = "radio" name="style" onchange = "fancy()"> BoringBetty <br>
			<button onclick="moo()"> Moo </button>
		</fieldset>
	</body>
</html>
