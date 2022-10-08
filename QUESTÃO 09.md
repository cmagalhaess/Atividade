import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner sc = new Scanner(System.in);
		int i, x, menor, maior;
		
		System.out.print("Informe um numero: ");
		x = sc.nextInt();
		menor = x;
		maior = x;
		
		for (i = 0; i <= 9; i++) {
			System.out.print("Informe outro numero: ");
			x = sc.nextInt();
			if (x > maior) {
				 maior = x;
			}
			else {
				menor = x;
			}
		}
		System.out.println("MENOR = "+ menor);
		System.out.println("MAIOR = "+ maior);
		sc.close();
	}
}
