# idade

<?php
   $idade = (int) readline();
   $resultado = veificaridade($idade);
   echo "$resultado";

   function veificaridade($idade){
    if ($idade <= 17){
        echo "voce é menor de idade!";
    }
     else {
        echo "voce é maior de idade";
    };

   }
?>
