import java.util.*;


public class Main
{
	public static void toplama(){
		
		Scanner in=new Scanner(System.in);
		System.out.println("İlk Sayıyı giriniz :");
		int a=in.nextInt();
		System.out.println("İkinci sayıyı giriniz :");
		int b=in.nextInt();
		System.out.println("Toplama :"+(a+b));
		
		
	}
	public static void cıkarma(){
		
	
		Scanner in=new Scanner(System.in);
		System.out.println("İlk Sayıyı giriniz :");
		int a=in.nextInt();
		System.out.println("İkinci sayıyı giriniz :");
		int b=in.nextInt();
		System.out.println("Çıkarma :"+(a-b));
		}
	public static void carpma(){
		Scanner in=new Scanner(System.in);
		System.out.println("İlk Sayıyı giriniz :");
		int a=in.nextInt();
		System.out.println("İkinci sayıyı giriniz :");
		int b=in.nextInt();
		System.out.println("Carpma :"+(a*b));
		}
	public static void bölme(){
		gir:
		for(;;){
			Scanner in=new Scanner(System.in);
			System.out.println("İlk Sayıyı giriniz :");
			int a=in.nextInt();
			System.out.println("İkinci sayıyı giriniz :");
			int b=in.nextInt();

			if(b==0){
				System.out.println("Payda 0 olamaz,Tekrar deneyiniz.");
				continue gir;

			}break;
		}
		}
		


	public static void main(String[] args){
		
		Scanner in=new Scanner(System.in);
		System.out.println("1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme");
		System.out.println("Seçim yapınız :");
		int islem=in.nextInt();
		switch (islem){
			case 1:
				toplama();
				break;
			
				case 2:
					cıkarma();
					break;
					case 3:
						carpma();
						break;
						case 4:
		
				bölme();
				break;
							
						
						
				
		
		
			
		}
		
		
		
		
	}
	}
