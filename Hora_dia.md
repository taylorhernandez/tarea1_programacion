var d=new Date();
var dia=new Array(7);

dia[0]="Domingo";
dia[1]="Lunes";
dia[2]="Martes";
dia[3]="Miercoles";
dia[4]="Jueves";
dia[5]="Viernes";
dia[6]="Sabado";
document.write("Hoy es: "  + dia[d.getDay()]  ) 


var fecha = new Date();
var mes = fecha.getMonth()+1;
var dia = fecha.getDate();
var año = fecha.getFullYear();
document.write(" <br> la hora es: " + mes + '-' + dia + '-' + año);

