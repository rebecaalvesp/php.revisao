# php.revisao
<?php
$valor1 = 5;
$valor2 = 10;
$resultado = ($valor1+$valor2)*($valor2/2);
echo $resultado;
>?

#portugol
#variavel1= 5
#variavel2=10
#resultado=(variavel1+variavel2)*(variavel2/2)
#escreva resultado
#escrever um codigo que receba 1 valor inteiro e exiba 15% desse valor

$valor= 100;
$porcentagem= $valor *0.15;
echo $porcentagem;


#portugol
#variavel = 100
#porcentagem = variavel*0.15
#escreva porcentagem=
echo"<br>";

#O cliente de uma loja realizou a compra de um produto e decidiu fazer o pagamento em doze parcelas iguais.
#para este parcelamento é cobrado juros de 1% ao mês escreva um codigo que calcule e exiba o valor total da 
#compra e o valor das parcelas.

$valor=1200;
$juros= $valor*0.12;
$total= $valor+$juros;
$parcela= $total/12;
echo $total."<br>";
echo $parcela;

#Escreva um codigo que receba um valor inteiro converta-o em anos,exiba a idade e informe se ele é maior ou
#de idade

$dias= 565;
$idade= $dias/365;
echo $idade;
if($idade>18){
    echo "MAIOR DE IDADE";
}else{
    echo "MENOR DE IDADE";
}




?>
#Escreva um codigo que receba um valor inteiro converta-o em anos,exiba a idade e informe se ele é maior ou
#de idade

$dias= 565;
$idade= $dias/365;
echo $idade;
if($idade>18){
    echo "MAIOR DE IDADE";
}else{
    echo "MENOR DE IDADE";
}
