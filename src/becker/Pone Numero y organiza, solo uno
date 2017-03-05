package becker;

import becker.robots.*;
import java.util.Scanner;

public class DeliverParcel
{
   public static void main(String[] args)
   {  
     // Set up the initial situation
      City prague = new City();
   
      Robot rob = new Robot(prague, 1, 0, Direction.EAST);
    
      // Direct the robot to the final situation
       Scanner lee= new Scanner(System.in);
       double n=lee.nextDouble();
    
       for(int i=0;i<n;i++){
           Thing bola= new Thing (prague, 2, 0);
       }
       for(int i=0;i<3;i++)
       {
         rob.turnLeft();
       }
       for(int i=0;i<1;i++)
       {
         rob.move();  
       }
       for(int i=0;i<n-1;i++)
       {
         rob.pickThing();  
       }
       rob.turnLeft();
       for(int i=0;i<n-1;i++){
       rob.move();
       rob.putThing();
       }
      for(int i=0;i<3;i++)
       {
         rob.turnLeft();
       }
      rob.move();
      for(int i=0;i<3;i++)
       {
         rob.turnLeft();
       }
      for(int i=0;i<n-1;i++){
      rob.move();
      }
     // karel.putThing();
      
      System.out.println(rob.countThingsInBackpack());
      
      
      
   }
}
