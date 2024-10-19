/* # assignment1
de 1
*/

package eternity_class;

import java.util.Scanner;

public class Eternitymain {
	/**
	 * @param args
	 */
	public static void main(String[] args) {
 Scanner scanner = new Scanner (System.in);
		System.out.println("nhap cgv1");
		double cgv1 = scanner.nextDouble();
		double  square2 = Math.pow(cgv1, 2);
		System.out.println("nhap cgv2");
		double cgv2 = scanner.nextDouble();
		double  square1 = Math.pow(cgv2, 2);
		double  squareroot = Math.sqrt(square1 + square2);
		// lam tron = roundedupsquare = math.round(number * 1x10X) / 1x10X
		double roundedupsquare = Math.round(squareroot * 1000.0) / 1000.0;
		System.out.println("gia tri chieu dai canh huyen tam giac vuong cua ban la " +  roundedupsquare );

//Cau2
			Scanner scanner = new Scanner (System.in);
			System.out.println("vui long nhap so a"); 
			double soA = scanner.nextDouble();
			System.out.println("vui long nhap n");
			int n = scanner.nextInt();
			int m = Math.abs(n);
			int x = 8;
			double sum = soA * x;
			double giatri = Math.pow(sum, m); 
			System.out.println("Vay don thuc P(x) =" + giatri);  	
	
//Cau3
			Scanner scanner = new Scanner (System.in);
			System.out.println("vui long nhap so n"); 
			int son = scanner.nextInt();
			if  (son < 10 ) {
				System.out.println("Vui long nhap 2 ky so");
			}else {
			int n = son / 10;
			int m = son % 10;
			int sum = n + m;
			System.out.println( "tong hai ky so cua n la " + sum);

De4
			Scanner scanner = new Scanner (System.in);
			System.out.println("vui long nhap 5 chu so khac nhau"); 
			double A = scanner.nextDouble();
			double B = scanner.nextDouble();
			double C = scanner.nextDouble();
			double D = scanner.nextDouble();
			double E = scanner.nextDouble();
			double sum = (double) A + B + C + D + E;
			int n = 5;
			double bientichluy = (double) sum / n;
			System.out.println("gia tri trung binh cua 5 chu so ban vua nhap la " + bientichluy);
De5
			Scanner scanner = new Scanner (System.in);
			System.out.println("vui long nhap gia tri do C");
			double celsius = scanner.nextDouble();
			double fahrenheit = (double) (celsius * 1.8) + 32;
			System.out.println("gia tri do C ban vua nhap sang do F la " + fahrenheit + "°F");

De6
			Scanner scanner = new Scanner (System.in);
			System.out.println("vui long nhap so tien vnd");
			int vnd = scanner.nextInt();
			int sum = vnd / 23500;
			int sum1 = vnd % 23500;
			double sum2 = (double) vnd / 23500;
			if ( sum1 != 0) {
				System.out.println("so tien vnd cua ban sang usd la " + sum + " du " + sum1);
				System.out.println("ban co muon tinh toan bo sang usd (nhan 1 neu co)");
				int what = scanner.nextInt();
				System.out.println("so tien vnd cua ban sang usd la " + sum2);	
			}else {
			System.out.println("so tien vnd cua ban sang usd la " + sum);
			}

}
}

