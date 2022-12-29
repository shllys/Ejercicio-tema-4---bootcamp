# Ejercicio-tema-4---bootcamp

public static void main(String[] args) {
    
  system.out.println("condicial if");
  int numeroIf = -2;
  if (numeroIf == 0) {
        system.out.println("El numero es cero");
  }  else if (numeroIf > 0) {
        system.out.println("El numero es positivo");
  }  else {
        system.out.println("El numero es negativo");
  }
  
  ----------------

  system.out.println("ciclo while");
  int numeroWhile = 0;
  while (numeroWhile < 3) {
    numeroWhile++;
    system.out.println(numeroWhile);
  }

  system.out.println("ciclo do-while");
  int numeroDoWhile = 3;
  do {
    system.out.println(numeroDoWhile);
    numeroDoWhile++;
  }  while (numeroDoWhile < 3);

  -----------------

  system.out.println("ciclo for");
  for (int numeroFor = 0; numeroFor <= 3; numeroFor++) {
    System.out.println(numeroFor);
  } 

  -----------------

  System.out.println("switch-case");
  int estacion = 0;
  switch (estacion){
    case 1:
       System.out.println("Esto es primavera");
       break;
    case 2:
       System.out.println("Esto es verano");
       break;
    case 3:
       System.out.println("Esto es otoño");
       break;
    case 4:
       System.out.println("Esto es invierno");
       break;
    default:
       System.out.println("Esto no es una estacion de año");
  }


} 
