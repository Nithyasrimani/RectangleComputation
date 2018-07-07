# RectangleComputation

import java.util.Scanner;  

public class RectangleComputation {   
   public static void main (String[] args) {
      
      int length, width, perimeter, area;
      Scanner in = new Scanner(System.in);  
      
      
      System.out.print("Enter the length: ");  
      length = in.nextInt();  
      System.out.print("Enter the width: ");
      width = in.nextInt();
      
    
      perimeter = length + length + width + width;
      area = length*width;
      
     
      System.out.println("The perimeter is: " + perimeter);
      System.out.println("The area is: " + area);
   }
}
