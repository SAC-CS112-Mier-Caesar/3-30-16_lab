# 3-30-16_lab

import java.util.Scanner;
import javax.swing.JOptionPane;


public class BirthYear { 
	public static void main(String[] args) { 
	
	  int cal;
	  int age;
	  int year;
	  
	  String name = JOptionPane.showInputDialog(" What is your name? );
  	String birthYear = JOptionPane..showInputDialog("What is your birth year? ");
  	
  	
   year = Integer.parseInt(birthYear);
   cal = Calendar.getIntance().get(Calendar.YEAR);
   age = cal - year;
   System.out.println("Hello, " + name + "You are " + age + " years old today");
   
   if (age > 21)
    System.out.println("You are lawfully allowed to drink alcohol.");
   
  

}
}
