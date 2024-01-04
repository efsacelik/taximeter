# taximeter
Calculates the prize in the taximeter.
package patikaAcademy;

import java.util.Scanner;

public class taksimetre {

	public static void main(String[] args) {
		
		Scanner input= new Scanner(System.in);
		
		System.out.println("Gidilen kilometreyi giriniz:");
		double km = input.nextDouble();
		
		double taksimetre = 2.20;
		double tutar = (km * 2.20)+10;
		tutar= (tutar<20)? 20 : tutar ;
		System.out.println("Toplam tutar: " + tutar);

	}

}
