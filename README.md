# pre--course-class-in-geekster-assignment-
// Take input from user and print greatest number among three numbers.

import java.util.Scanner;  
public class Main
{
	public static void main(String[] args) {
	    int x, y, z, largest, temp;  
//object of the Scanner class  
Scanner sc = new Scanner(System.in);  
  
System.out.println("Enter the first number:");  
x = sc.nextInt();  
System.out.println("Enter the second number:");  
y = sc.nextInt();  
System.out.println("Enter the third number:");  
z = sc.nextInt();  

temp=x>y?x:y;
largest=z>temp?z:temp;  
System.out.println("The largest number is: "+largest);
	
	}
}

