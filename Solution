<?php

$handle = fopen ("php://stdin","r");
fscanf($handle,"%d",$n);
$arr_temp = fgets($handle);
$arr = explode(" ",$arr_temp);
$arr = array_map('intval', $arr);
 $cp=0;
 $cn=0;
 $cz=0;
 
 
  for($i=0;$i<count($arr);$i++){
      if($arr[$i]>0) $cp=$cp+1;
      elseif ($arr[$i]<0) $cn=$cn+1;
      else $cz=$cz+1;

      
  }
$x=$cp/($cp+$cn+$cz);
$y=$cn/($cp+$cn+$cz);
$z=$cz/($cp+$cn+$cz);
 echo number_format(strval($x), 5 );
echo("\n");
 echo number_format(strval($y), 5 );
echo("\n");
 echo number_format(strval($z), 5 );
echo("\n");
 


?>
