# type conversion (conversão de tipo) / type coercion ( correção de tipo)

...js
var x = number ("0") //type conversion , nessa linha é feita um conversão de tipo explicita

var y = "2" +3 // type coercion , nessa linha é feita uma conversão implicito do valor 3 que é numerico (number) para texto (string)

//onde usa expressões e repetição ,faz necessario um valor boolean (verdadeiro ou falso)
//Ex.
if(true){
}

//caso não for informada uma expressão ou um valor boolean diretamente,ele ferá um type coercion (coeção de tipo)
//Ex.
if (0) { //Nessa linha ele ira fazer uma conversão de 0 para um boolean (verdadeiro ou falso),nesse caso 0 será falso
}
...
