
var año;

  año=prompt('Ingrese el Año:','');

  año=parseInt(año)


 if ((((año%100)!=0)&&((año%4)==0))||((año%400)==0)){

  document.write('El año es bisiesto: ');

 }

 else{document.write('El año no es bisiesto: ');}


