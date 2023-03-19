# actividad2_punto4_poo
package mayormenor;
import java.util.Scanner;
public class Mayormenor {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        double  valor1,valor2;
        Scanner ingresot = new Scanner (System.in);
        
        System.out.println("Ingrese el valor 1:  ");
        valor1 = ingresot.nextDouble();
        
        System.out.println("Ingrese valor 2:  ");
        valor2 = ingresot.nextDouble();
        
        if (valor1<valor2){
            System.out.println(valor1 +" es menor que "+ valor2);
        } else if (valor2<valor1){
            System.out.println(valor1 +" es mayor que "+ valor2);
        }
        else {
            System.out.println(valor1 +" es igual que "+ valor2);
        }
        
    }
    
}
