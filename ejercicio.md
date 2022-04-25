import java.util.*;

public class Main 
{
    //HECHO POR JHON BARREIRO SANTOS
    public static void main(String[] args) {
        // Your code here!
        
        int resultado;
        
        resultado = suma(5,5,5);
        System.out.println(resultado);
        
        coche miCoche;
        miCoche = new coche();
        
        miCoche.quitarPuertas();
        System.out.println(miCoche.puertas);

    }
   
    public static int suma(int a, int b, int c){
        return a + b + c;
    }
        
    class coche{
        public int puertas = 0;
        
        public void quitarPuertas(){
            this.puertas++;
        }
    }    
}
