package Alice_Pilhas;

import java.util.Scanner;

class Pilhas_Impar_Par {

	public Pilhas_Impar_Par() {
		// TODO Auto-generated constructor stub
		
		Scanner tcd = new Scanner(System.in);
		
		System.out.println("Informe o número");
		
		int número = tcd.nextInt();
		
		if( número % 2 == 0 ) {
			System.out.println("Número é par");
		} else {
			System.out.println("Número é ímpar");
			
		}
	}

}
