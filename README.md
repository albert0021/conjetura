package proyecto_factorial;

import java.util.Scanner;
import java.util.Scanner;

public class Proyecto_Factorial {

    public static void main(String[] ARGS) {
        Scanner obtenerNumero = new Scanner(System.in);
        int contador, I, numero;

        System.out.print("Ingresa un numero: ");
        numero = obtenerNumero.nextInt();

        contador = 0;

        for (I = 1; I <= numero; I++) {
            if ((numero % I) == 0) {
                contador++;
            }
        }

        if (contador <= 2) {
            System.out.println("El numero es primo");
        } else {
            System.out.println("El numero no es primo");
        }
    }

    public class FactorialNumero {

        //Ej.: El factorial de 5 es: 5*4*3*2*1
        long factorial = 1;
        int num;
        Scanner numero = new Scanner(System.in);

        System.out.print ("Introduce un número: ");
        num  = numero.nextInt();
        for (int i = num; i > 0; i --) {
            factorial = factorial * i;
        }

        System.out.println ("El factorial de " + num + " es: " + factorial);
        
        
       

class SumarDigitos {

    public static void main(String[] args) {

        Scanner miScanner = new Scanner(System.in);

        int numero;

        int resultado = 0;

       

        System.out.print("Introduce un número para sumar sus dígitos: ");

        numero = miScanner.nextInt();

       

        while(numero > 0) {

            resultado += numero % 10;

            numero = numero / 10;

        }

        System.out.println("La suma es: " + resultado);

}
