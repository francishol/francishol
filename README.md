package calculadora;
import java.util.Scanner;
public class Callll {

	
	public static void main(String[] args) {
		int sair = 6;
		int n1, n2;
	
		
		do{
			System.out.println("-______________________CALCULADORA_______________-");
			System.out.println("Digite os numeros");
			
		    Scanner E = new Scanner (System.in);
		    n1 = E.nextInt();
		    n2 = E.nextInt();
		    System.out.println("1. Somar");
			System.out.println("2. Subtrair");
			System.out.println("3. Multiplicar");
			System.out.println("4. Dividir");
			System.out.println("5. Media");
			System.out.println("6. Sair");
			sair = E.nextInt();
			double r1 = n1 + n2, r2 = n1 - n2, r3 = n1 * n2, r4 = n1 / n2, r5 =(n1 + n2)/2;
			switch (sair){
			case 1:
				System.out.println("Resultado "+r1);
				break;
			case 2:
				System.out.println("Resultado "+r2);
				break;
			case 3:
				System.out.println("Resultado "+r3);
				break;
			case 4:
				System.out.println("Resultado "+r4);
				break;
			case 5:
				System.out.println("Resultado "+r5);
			    break;
			case 6:
				System.out.println("Obrigado por usar nossa apliacacao:)"+"\n"+"By @francishol");
				break;
				
				default:
					System.out.println("Opcao invalida....");
			}
			
		}while(sair != 6);
	

	}

}
