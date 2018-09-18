import java.io.*;
import java.util.*;

public class HuxleyCode {
  public static void main(String args[]) {
    	Scanner in = new Scanner(System.in);
		String Pessoa1, Pessoa2, Pessoa3, Pessoa4, Pessoa5, Posi��o1, Posi��o2 = "", Posi��o3 = "", Posi��o4 = "", Posi��o5 = "";
		
		Pessoa1 = in.nextLine();									
		Pessoa2 = in.nextLine();
		Pessoa3 = in.nextLine();
		Pessoa4 = in.nextLine();
		Pessoa5 = in.nextLine();
		
		Posi��o1 = "Princesa";
			
		if (Pessoa2.equals("Mario") && Pessoa4.equals("Toad") || Pessoa2.equals("Toad") && Pessoa4.equals("Mario")) {
			Posi��o2 = "Mario";
			Posi��o4 = "Toad";
		}
		
		if (Pessoa3.equals("Mario") && Pessoa5.equals("Toad") || Pessoa3.equals("Toad") && Pessoa5.equals("Mario")) {
			Posi��o3 = "Mario";
			Posi��o5 = "Toad";
		}
		
		if (Pessoa2.equals("Yoshi") && Pessoa4.equals("Mario") || Pessoa2.equals("Mario") && Pessoa4.equals("Yoshi"))	{
			Posi��o2 = "Mario";
			Posi��o4 = "Yoshi";
		}	
		
		if (Pessoa3.equals("Yoshi") && Pessoa5.equals("Mario") || Pessoa3.equals("Mario") && Pessoa5.equals("Yoshi"))	{
			Posi��o3 = "Mario";
			Posi��o5 = "Yoshi";
		}	
		
		if (Pessoa2.equals("Luigi") && Pessoa4.equals("Mario") || Pessoa2.equals("Mario") && Pessoa4.equals("Luigi"))	{
			Posi��o2 = "Mario";
			Posi��o4 = "Luigi";
		}	
		
		if (Pessoa3.equals("Luigi") && Pessoa5.equals("Mario") || Pessoa3.equals("Mario") && Pessoa5.equals("Luigi"))	{
			Posi��o3 = "Mario";
			Posi��o5 = "Luigi";
		}	
		
		if (Pessoa2.equals("Luigi") && Pessoa4.equals("Yoshi") || Pessoa2.equals("Yoshi") && Pessoa4.equals("Luigi")) {
			Posi��o2 = "Luigi";
			Posi��o4 = "Yoshi";
		}
		
		if (Pessoa3.equals("Luigi") && Pessoa5.equals("Yoshi") || Pessoa3.equals("Yoshi") && Pessoa5.equals("Luigi")) {
			Posi��o3 = "Luigi";
			Posi��o5 = "Yoshi";
		}
		
		if (Pessoa2.equals("Luigi") && Pessoa4.equals("Toad") || Pessoa2.equals("Toad") && Pessoa4.equals("Luigi")) {
			Posi��o2 = "Toad";
			Posi��o4 = "Luigi";
		}
				
		if (Pessoa3.equals("Luigi") && Pessoa5.equals("Toad") || Pessoa3.equals("Toad") && Pessoa5.equals("Luigi")) {
			Posi��o3 = "Toad";
			Posi��o5 = "Luigi";
		}
		
		if (Pessoa2.equals("Yoshi") && Pessoa4.equals("Toad") || Pessoa2.equals("Toad") && Pessoa4.equals("Yoshi"))	{
			Posi��o2 = "Toad";
			Posi��o4 = "Yoshi";
		}	
		
		if (Pessoa3.equals("Yoshi") && Pessoa5.equals("Toad") || Pessoa3.equals("Toad") && Pessoa5.equals("Yoshi"))	{
			Posi��o3 = "Toad";
			Posi��o5 = "Yoshi";
		}		
			
		
			
				System.out.printf("%s\n%s\n%s\n%s\n%s\n",Posi��o1,Posi��o2,Posi��o3,Posi��o4,Posi��o5);
  }
}
