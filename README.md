# Unit-10

Problem #1

<!DOCTYPE HTML>
<html>
<head>
<script src="htpps://ajax.googleapis.com/ajax/libs//jquery/3.1.1/jquery.min.js"></script>
	<script>
	$ (document).ready (function(){
	
	});
	</script>
	
	</head>
	<body>
	
	<div style="background:#98bf21;height:20px;width:600px;">Hello World
	$("button").click(function(){
    $("#box").animate({height: "100px"});
	});</div>
	
});
	
	</body>
	</html>
  
  
  Problem #2
  
  <!DOCTYPE HTML>
<html>
<head>
<script src="htpps://ajax.googleapis.com/ajax/libs//jquery/3.1.1/jquery.min.js"></script>
<script>
$ (document).ready (function(){
	
});
</script>
	
</head>
<body>
	
<p> This is a paragraph.</p>
<p> This is another paragraph.</p>

$("p").click(function(){
alert("The paragraph was clicked.");
});

<ol>
	<li>List item 1</li>
	<li>List item 2</li>
	<li>List item 3</li>
</ol>
	$("button").click(function(){
    $("p").append("<b>Appended text</b>");
});

	<button id="btn1">Append text</buttton>
	<button id="btn2">Append list items</buttton>
	
</body>
</html>
