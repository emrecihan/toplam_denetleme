package agoritma5;

import java.util.Scanner;

public class algoritma5class3 {

	public static void main(String[] args) {
		// veri yarat.
				int sayi1,sayi2;
				sayi1=(int)(Math.random()*10);
				sayi2=(int)(Math.random()*10);
				int cevap;
				
				
				//sayi1=(int)(System.currentTimeMillis()%10);
				//sayi2=(int)(System.currentTimeMillis()%10 %10);
				System.out.println("sayi1=" +sayi1+ "sayi2=" + sayi2);
				
				
				//kullanıcıdan cevabı al.
				Scanner input=new Scanner(System.in);
				System.out.println("iki sayının toplamını giriniz");
				cevap=input.nextInt();
				
				//cevaba bağlı olarak mesaj göster.
				System.out.println("cevap doğru mu=" + (cevap==sayi1+sayi2));

	}

}
