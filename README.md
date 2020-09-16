# Assignment-2
import java.util.Scanner;
public class wifidiagnosis {

	public static void main(String[] args) {
		
		    int input;
		    Scanner keyboard = new Scanner(System.in);
		    
		    System.out.println("Please reboot your computer");
		    
		    System.out.println(" Did that fix the problem? Type 1 for yes 2 for no");
		    
		    input = keyboard.nextInt(); 
		    if (input == 2)
		  {
		       System.out.print("Please reboot the router.");
		    
		    System.out.println(" Did that fix the problem? Type 1 for yes 2 for no");
		         input = keyboard.nextInt();
		        if (input == 2)
		       {
		        System.out.print("Please make sure the cables to your router are plugged in firmly and your router is getting power.");
		         
		        System.out.println(" Did that fix the problem? Type 1 for yes 2 for no");
		        input = keyboard.nextInt();
		          if (input == 1)
		          {
		        	  System.out.println("Plugging in the cables firmly seeems to work.");
		          }
		                 System.exit(0);
		                 
		           }
		       }
		    
		  }
		
		

	}


