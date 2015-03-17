import java.util.*;
public class benda
{
	public static void main(String[]args)
	{
		Scanner input=new Scanner(System.in);
		int temperatur;
		
		System.out.println("masukkan temperatur:");
		temperatur = input.nextInt();
		
		if(temperatur <=0)
		{System.out.println("padat");
		}
		else if (temperatur >0 && temperatur <=100)
		{
			System.out.println("cair");
		}
		else 
		{
			System.out.println("gas");
		}
		
		
	}
}
