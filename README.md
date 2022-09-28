# java-scanner
gamit ug scanner to input kung unsay gipangayo like name, age or address

package oopexercise;

import java.util.Scanner;

public class computesumaverage {

	public static void main(String[] args) {
		
		Scanner scanVar = new Scanner(System.in);
		
		System.out.println("what is your name? ");
		String name = scanVar.nextLine();
		
		System.out.println("what is your number? ");
		long number = scanVar.nextInt();
		
		
		System.out.println("Hello, " + name);
		System.out.println("Your number is " + number);
		System.out.println("Hello, " + name + ". It's nice to have your number. " + number );
		
		

	}
}
