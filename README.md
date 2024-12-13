# TaVanDo.php
https://quera.org/problemset/616
<?php
$n = (int)readline("Enter a number: ");
$tavan = 2;
if ($n >= 1 and $n <= 10 ** 9){
	while($n >= $tavan){
		$tavan *= 2;
	}
}
echo $tavan;
