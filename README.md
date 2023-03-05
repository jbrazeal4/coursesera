<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>MENU</title>
<style>

*{
	box-sizing:border-box;
}
h1{
	text-align:center;
}
#chicken{
	text-align:center;
	width:200px;
	margin-top:auto;
	margin-left:auto;
	border:2px solid black;
	background-color:red;
	font-family:helvetica;
}
#beef{
text-align:center;
	width:200px;
	margin-top:auto;
	margin-left:auto;
	border:2px solid black;
	background-color:blue;
	font-family:helvetica;
}
#sushi{
text-align:center;
	width:200px;
	margin-top:auto;
	margin-left:auto;
	border:2px solid black;
	background-color:green;
	font-family:helvetica;
}
p{
	text-align:left;
	margin-bottom:50px;
	margin-left:5px;
	color:white;
	display:flex;
	justify-content:center;
	font-family:helvetica;
}
.row{
	width:100%;
}
/* Display on Large Screen */

	@media (min-width:992px){
		.col-lg-1, .col-lg-2, .col-lg-3{
			border:2px solid black;
			float:left;
			margin-left:100px;
			margin-right:-50px;
		}
		.col-lg-1{
			width:25%;
			background-color:green;
		}
		.col-lg-2{
			width:25%;
			background-color:red;
		}
		.col-lg-3{
			width:25%;
			background-color:blue;
		}
	}
	@media (min-width:768px) and (max-width:991px){
		.col-md-1, .col-md-2, .col-md-3{
			border:2px solid black;
			float:left;
			margin-left:25px;
		}
		.col-md-1{
			width:45%;
			background-color:green;
			margin-right:10px;
		}
		.col-md-2{
			width:45%;
			background-color:red;
		}
		.col-md-3{
			width:94%;
			background-color:blue;
			margin-top:30px;
		}
	}
	@media (max-width:767px){
		.col-sm-1, .col-sm-2, .col-sm-3{
			float:left;
			border:2px solid black;
		}
		.col-sm-1{
			width:100%;
			background-color:green;
		}
		.col-sm-2{
			width:100%;
			background-color:red;
			margin-top:30px;
		}
		.col-sm-3{
			width:100%;
			background-color:blue;
			margin-top:30px;
		}
	}
</style>
</head>
<body>
	<h1>Menu</h1>
	<div class="row">
		<div class="col-lg-1 col-md-1 col-sm-1"><h2 id="chicken">Chicken</h2><p>This might be the most fun class I've ever taken.</p></div>
		<div class="col-lg-2 col-md-2 col-sm-2"><h2 id="beef">Beef</h2><p>This might be the most fun class I've ever taken.</p></div>
		<div class="col-lg-3 col-md-3 col-sm-3"><h2 id="sushi">Sushi</h2><p>This might be the most fun class I've ever taken.</p></div>
</div>
</body>
</html>



