# 3-30-16_lab

import java.util.Scanner;
import javax.swing.JOptionPane;


public class BirthYear { 
	public static void main(String[] args) { 
	
	  int cal;
	  int age;
	  int year;
	  int yearsLeft;
	  int count = 0;
	  
	  while (count < 3){
	  
	  String name = JOptionPane.showInputDialog("What is your name? ");
  	String birthYear = JOptionPane.showInputDialog("What is your birth year? ");
  	
  	
   year = Integer.parseInt(birthYear);
   cal = Calendar.getIntance().get(Calendar.YEAR);
   age = cal - year;
   System.out.println("Hello, " + name + "You are " + age + " years old today");
   
   if (age > 21)
    System.out.println("You are legally allowed to drink alcohol.");
   
   yearsLeft = 21 - age;
   
   if (age <21)
   System.out.pritnln("You have " + yearsLeft + " until you can legally drink");
   
   count++
   }
  

}
}
