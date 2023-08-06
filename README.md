# Java-Program-for-calculating-the-Area-of-a-circle

Area of a circle using Java :
Here, in this page we will write the program to find area of circle using java. The area of a circle is the number of square units inside the circle. If we know the radius of the circle, then we can directly calculate the area by using a standard formula, 

A = π * (radius * radius)



Working:-
Calculate the area by using the standard formula:
      A = π * (radius * radius)

             or

     A = π * (diameter * diameter)/4

Print the result.
Code in Java using Radius
Run
//Java program to calculate area of a circle
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
			
		double radius = 7;			
		
        //formula for area of a circle
		double area = 3.14 * radius * radius;		
		System.out.println(area);
		
	}
}
Output
153.86
Code in Java using Diameter
Run
//Java program to calculate area of a circle
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
			
		double d = 14;			
		
                //formula for area of a circle
		double area = (3.14 * d * d)/4;		
		System.out.println(area);
		
	}
}
Output
153.86
