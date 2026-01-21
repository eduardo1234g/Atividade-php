<?php
  $num1 = 5;
  $num2 = 10;
  
  $soma1 = ($num1 + $num2);
  
  echo "A soma entre $num1 e $num2 é igual a: $soma1 \n";
  
  //Outra atividade
  
  $A = 3;
  $B = 7;
  $C = 4;
  
  $soma2 = ($A + $C) > $B;
  $soma3 = $B >= ($A + 2);
  $soma4 = $C == ($B - $A);
  $soma5 = ($B + $A) <= $C;
  $soma6 = ($C + $A) > $B;
  $soma7 = ($A + $B + $C) >= 16;
  $soma8 = ($A + $B + $C) <= 14;
  
  echo "(A + C) > B é igual a: " . ($soma2 ? 'true' : 'false');
  echo "\nB >= (A + 2) é igual a: " . ($soma3 ? 'true' : 'false');
  echo "\nC = (B - A) é igual a: " . ($soma4 ? 'true' : 'false');
  echo "\n(B + A) <= C é igual a: " . ($soma5 ? 'true' : 'false');
  echo "\n(C + A) > B é igual a: " . ($soma6 ? 'true' : 'false');
  echo "\n(A + B + C) >= 16 é igual a: " . ($soma7 ? 'true' : 'false');
  echo "\n(A + B + C) <= 14 é igual a: " . ($soma8 ? 'true' : 'false');
  
  $TabuadaValor = 8;
  $Resultadodemultiplicacao1 = (1 * $TabuadaValor);
  $Resultadodemultiplicacao2 = (2 * $TabuadaValor); 
  $Resultadodemultiplicacao3 = (3 * $TabuadaValor); 
  $Resultadodemultiplicacao4 = (4 * $TabuadaValor); 
  $Resultadodemultiplicacao5 = (5 * $TabuadaValor); 
  $Resultadodemultiplicacao6 = (6 * $TabuadaValor); 
  $Resultadodemultiplicacao7 = (7 * $TabuadaValor); 
  $Resultadodemultiplicacao8 = (8 * $TabuadaValor); 
  $Resultadodemultiplicacao9 = (9 * $TabuadaValor); 
  $Resultadodemultiplicacao10 = (10 * $TabuadaValor); 
  
  echo "\n ---------------------- \n TABUADA \n ---------------------- \n";
  echo "\n8 x 1 = $Resultadodemultiplicacao1";
  echo "\n8 x 2 = $Resultadodemultiplicacao2";
  echo "\n8 x 3 = $Resultadodemultiplicacao3";
  echo "\n8 x 4 = $Resultadodemultiplicacao4";
  echo "\n8 x 5 = $Resultadodemultiplicacao5";
  echo "\n8 x 6 = $Resultadodemultiplicacao6";
  echo "\n8 x 7 = $Resultadodemultiplicacao7";
  echo "\n8 x 8 = $Resultadodemultiplicacao8";
  echo "\n8 x 9 = $Resultadodemultiplicacao9";
  echo "\n8 x 10 = $Resultadodemultiplicacao10";
?>
