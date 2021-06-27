# PHP-sideHustle

	<?php

	    function numRange($start, $end){        
	        while ($start <= $end) {
	           echo $start . "<br>";
	            $start++;
	        }   
	    }
	    numRange(6, 11);

	    echo "<br>". "<br>";

	    function sum1($min, $max){
	        $total = 0;
	        for ($i=$min; $i <= $max; $i++) { 
	            $total += $i;            
	        }  
	        echo ($total);  
	    }
	    sum1(1, 3);

	?>
