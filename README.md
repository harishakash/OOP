# OOP
package akash;
import java.util.Scanner;
class car{
	String model;
	String color;
	car(String model,String color){
		this.model=model;
		this.color=color;
	}
	 void start()
	 {
		 System.out.println(model+"car is staring.");
		 System.out.println("car color is"+color);
		
	 }
	 void stop()
	 {
		 System.out.println(model+"car is stop.");
	 }
	
}
public class classsamlpe 
{
 public static void main(String[] args) 
 {
	 Scanner cars= new Scanner(System.in);
	 System.out.println("Enter car model");
	 String model =cars.nextLine();
	 System.out.println("Enter car color");
	 String color =cars.nextLine();
	 car mycar=new car(model,color);
	 mycar.start();
	 mycar.stop();
	 cars.close();
 
 }
}
