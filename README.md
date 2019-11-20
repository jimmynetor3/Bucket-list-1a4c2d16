<?php 



$count = readline("welk getal wil je");

if (is_numeric($count)) {
	echo " ";
}
else{
	exit("je zuigt");
}


$arraytest = array();

for ($i=0; $i < $count; $i++) { 
	echo('moet je?' . PHP_EOL);
	$anwer = readline();
	array_push($arraytest, $anwer);
}


for ($i=0; $i < count($arraytest); $i++) { 
	echo($arraytest[$i] . PHP_EOL);
}

 ?>