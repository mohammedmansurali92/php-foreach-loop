# php-foreach-loop
<?php
/* php loop, while loop, for loop, for each loop, do while loop;
while()
	statement; */
/*foreach($array as $value){
	statement;
}
foreach($array as $key>= $value){
	statement;
}*/
$a=array(10,20,30,40);
foreach($a as $c){
	echo $c."<br>";
	echo "<br>";
}
$colors= array("a"=>"red","b"=>"green", "c"=>"blue");
foreach($colors as $d){
	echo $d."<br>";
}
echo "<br>.<br>";
$cars= array("a"=>"Volvo", "b"=>"BMW", "c"=>"Mercedes", "d"=>"Toyota");
foreach($cars as $key=> $e){
	echo $key." .".$e ."<br>";
}
echo "<br><br>";
$name= array("First_Name"=>"Mohammedmansur", "Last_Name"=>"Ali");
foreach($name as $key=>$c){
	echo $key. " :".$c."<br>";
}
?>
