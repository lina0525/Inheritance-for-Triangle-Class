package com.company;  
import java.util.Scanner;  
 public class Main {  
    public static void main(String[] args) {  
        Scanner input = new Scanner(System.in);  
        System.out.println("Enter three sides of the Triangle");  
        double side1 = input.nextDouble();  
        double side2 = input.nextDouble();  
        double side3 = input.nextDouble();  
  
        System.out.println("Enter the color of the Triangle");  
        String color = input.next();  
  
        System.out.println(" Is the Triangle filled? Reply with 'True' or 'False' ");  
  
        String filled = input.next();  
    }  
    protected Geometrict(){  
        dataCreated=new java.util.Date();  
    }  
     public GeometricObject(String color, boolean filled) {  
         dataCreated=new java.util.Date();  
         this.color = color;  
         this.filled = filled;  
     }  
     public String getColor() {  
         return color;  
     }  
  
     public void setColor(String color) {  
         this.color = color;  
     }  
  
     public boolean isFilled() {  
         return filled;  
     }  
  
     public void setFilled(boolean filled) {  
         this.filled = filled;  
     }  
  
     public java.util.Date getDateCreated() {  
         return dateCreated;  
     }  
  
     public String toString() {  
         return "Created on " + dateCreated + "\n color: " + color + " and filled ";  
     }  
 }  
     public new Triangle(side1, side2, side3){  
        System.out.println("The Triangle Sides are \n side 1: " + side1 + "\n Side 2: " + side2 + "\n Side 3: " + side3);  
        System.out.println("The Triangle's Area is " + (side1 + side2 + side3) / 2);  
        System.out.println("The Triangle's Perimeter is "+ (side1 + side2 + side3));  
        System.out.println("The Triangle's Color is " +Color);  
        System.out.println("Is the Triangle filled? " + filled);  
         }  
    }  
  }  
