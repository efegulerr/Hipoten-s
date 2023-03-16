# Hipoten-s
//patika.dev ödevi hipotenüs

import java.util.Scanner;
public class main {
    public static void main(String[] args) {
        int uzun, kisa;
        double hipo;
        System.out.println("1. kenarı giriniz");
        Scanner inp = new Scanner(System.in);
        uzun = inp.nextInt();
        System.out.println("2. kenarı giriniz");
        Scanner idv = new Scanner(System.in);
        kisa = idv.nextInt();
        hipo = Math.sqrt ((uzun*uzun) + (kisa*kisa));
        System.out.println("Hipotenüs :"+ hipo);
        

    }

    

}
