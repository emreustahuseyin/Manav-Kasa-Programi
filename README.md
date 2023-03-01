# Manav-Kasa-Programi


import java.util.Scanner;

public class manav {

    public static void main(String[] args) {

        double armut, elma, domates, muz, patlican;
        double perArmut = 2.14, perElma = 3.67, perDomates=1.11, perMuz=0.95, perPatlican=5;


        Scanner input = new Scanner(System.in);

        System.out.println(" Armut Kaç Kg ? ");
        armut = input.nextDouble();

        System.out.println(" Elma Kaç Kg ? ");
        elma = input.nextDouble();

        System.out.println(" Domates Kaç Kg ? ");
        domates  = input.nextDouble();

        System.out.println(" Muz Kaç Kg ? ");
        muz = input.nextDouble();

        System.out.println(" Patlican Kaç Kg ? ");
        patlican = input.nextDouble();

        double sonuc = (armut * perArmut) + (elma*perElma) + (domates*perDomates) + (muz*perMuz) + (patlican*perPatlican);
        System.out.println(" Sepetinizin Tutari " + sonuc );
    }

    }

