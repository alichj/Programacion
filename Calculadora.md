# Programacion
package tarea01;
import java.util.Scanner;
public class Tarea01 {
    static Scanner entrada=new Scanner (System.in);
    public static void main(String[] args) {
      
        System.out.println("Ingrese numero 1");
        int numeroUno=entrada.nextInt();
        System.out.println("Ingrese numero 2");
        int numeroDos=entrada.nextInt();
       
    }
    public class Calculadora{
        private int Suma(int numeroUno,int numeroDos){
            int resultadoSuma;
            return resultadoSuma=numeroUno+numeroDos;
        }
        private int Resta(int numeroUno,int numeroDos){
            int resultadoResta;
            return resultadoResta=numeroUno-numeroDos;
        }
        private int Multiplicacion(int numeroUno,int numeroDos){
            int resultadoMultiplicacion;
            return resultadoMultiplicacion=numeroUno*numeroDos;
        }
        private double Division(int numeroUno,int numeroDos){
            int resultadoDivision;
            return resultadoDivision=numeroUno/numeroDos;
        }
    }
}
