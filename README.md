# patika.dev 
hipotenusHesaplama
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int a, b ;
        double c ;

        Scanner inp = new Scanner(System.in);

        System.out.print("a kenarını giriniz: ");
        a = inp.nextInt();
        System.out.print("b kenarı giriniz");
        b = inp.nextInt();
        c = Math.sqrt((a*a) + (b*b));
        System.out.println("c kenarı : " + c);

    }
}
