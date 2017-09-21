<!doctype html>
<html>
<head>
<title> Media voti </title>
</head>
<body>
<?php
/*
* calcolo della media dei voti 
*/ 
$voti = array (7,7,7,9,8,7,9,7,8);
$limite = count ($voti);
$i = 0;
$somma = 0;
while ($i <$limite)
{ 
$somma += $voti [$i];
$i++;
}
$media = $somma / $limite;
echo "<h2>media dei voti: " . $media . "</h2>";
?>
</body>
</html>
