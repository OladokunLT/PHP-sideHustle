# PHP-sideHustle

	<?php

	    function range($start, $end){        
	        while ($start <= $end) {
	           echo $start . "<br>";
	            $start++;
	        }   
	    }
	    range(6, 11);

	    echo "<br>". "<br>";

	    function sum($min, $max){
	        $total = 0;
	        for ($i=$min; $i <= $max; $i++) { 
	            $total += $i;            
	        }  
	        echo ($total);  
	    }
	    sum(1, 3);

	?>
