
var min = 1;
    var max = 10;
    var aleatorio = Math.floor(Math.random() * max - min + 1) + min;
    var intentos = 0;
    var nombre = prompt('Bienvenido al juego Adivina, Escribe tu nombre');
    var numero;

    while(intentos < 5){
        numero = parseInt(prompt(nombre+' ,ingresa un numero entre el '+min+' y el '+max));

        if(numero >= min && numero <= max){
            if(numero < aleatorio){
                alert('El numero no corresponde');
            } else if(numero > aleatorio){
                alert('El numero no corresponde');
            } else if(numero == aleatorio){
                break;
            }
        } else {
            alert('Debe ingresar un numero entre '+min+' y '+max);
        }
        intentos++;
    }

    if(numero == aleatorio){
        alert('Buen Trabajo  '+(intentos + 1)+' intentos.');
    } else {
        alert('Agotaste el numero de intentos, suerte para la proxima!!!');
    }








