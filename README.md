//These rates of currency are according to 28Aug 
import java.util.*;
class  currencyconverter{
	public static void main(String[] args) { 
		 System.out.println("CURRENCY CONVERTER");
		 System.out.println("-----------------------------------");
		 System.out.println("Enter your choice");
		System.out.println("1:Rupees to US Dollar");
	    System.out.println("2:US Dollar to Rupees");
		System.out.println("3:Rupees to Euro");
		System.out.println("4:Euro to Rupees");
		System.out.println("5:Euro to US Dollar");
		System.out.println("6:US Dollar to Euro");
		System.out.println("7:Rupees to British Pound");
		System.out.println("8:British Pound to Rupees");
		System.out.println("9:British Pound to Dollar");
		System.out.println("10:Dollar to British Pound");
		System.out.println("Enter 11 to exit");
		Scanner sc=new Scanner(System.in);	
		int a;
		do{
		a=sc.nextInt();	
		switch(a){
			case 1:System.out.print("Enter Amount in Rupees:");
			       double Rupees=sc.nextDouble();  
			       System.out.println("The amount in Dollar is: "+Rupees*0.012+"$");
				   System.out.println("_________________________________________________");
				   break;
			case 2:System.out.print("Enter Amount in Dollar:");
			       double Dollar=sc.nextDouble();
			       System.out.println("The amount in Rupees is: "+Dollar*83.87+"Rs");
				   System.out.println("_________________________________________________");
				   break;
			case 3:System.out.print("Enter Amount in Rupees:");
			       double R=sc.nextDouble();
			       System.out.println("The amount in Euro is: "+R*0.011+"Euro");
				   System.out.println("_________________________________________________");
				   break;
			case 4:System.out.print("Enter Amount in Euro:");
			       double Euro=sc.nextDouble();
			       System.out.println("The amount in Rupees is: "+Euro*92.53+"Rs");
				   System.out.println("_________________________________________________");
				   break;
			case 5:System.out.print("Enter Amount in Euro:");
			       double E=sc.nextDouble();
			       System.out.println("The amount in Dollar is: "+E*1.1026848+"$");
				   System.out.println("_________________________________________________"); 
				   break;
			case 6:System.out.print("Enter Amount in Dollar:");
			       double D=sc.nextDouble();
			       System.out.println("The amount in Euro is: "+D*0.90687744+"Euro");
				   System.out.println("_________________________________________________"); 
				   break;
			case 7:System.out.print("Enter Amount in Rupees:");
			       double Rs=sc.nextDouble();
			       System.out.println("The amount in Pound is: "+Rs*0.0092+"Pound");
				   System.out.println("_________________________________________________"); 
				   break;
			case 8:System.out.print("Enter Amount in Pound:");
			       double Pound=sc.nextDouble();
			       System.out.println("The amount in Rupees is: "+Pound*108.56+"Rs");
				   System.out.println("_________________________________________________"); 
				   break;
			case 9:System.out.print("Enter Amount in Pound:");
			       double P=sc.nextDouble();
			       System.out.println("The amount in Dollar is: "+P*1.29+"$");
				   System.out.println("_________________________________________________"); 
				   break;
			case 10:System.out.print("Enter Amount in Dollar:");
			       double Dr=sc.nextDouble();
			       System.out.println("The amount in Pound is: "+Dr*0.77+"Pound");
				   System.out.println("_________________________________________________"); 
				   break;
			case 11:System.out.println("EXIT");	  
			        break;
			default:System.out.println("Please enter valid number");
		}
		}
		while (a!=11);
		}	
}
