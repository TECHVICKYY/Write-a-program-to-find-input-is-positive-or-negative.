# Write-a-program-to-find-input-is-positive-or-negative.
import java.util.*;
import java.util.Scanner;

public class A1_Ex5 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int num;
		 System.out.println("Enter a number ::");
		 Scanner sc= new Scanner(System.in);
		 num = sc.nextInt();
		 if (num > 0){
		 System.out.println("Given number is a positive integer");
		 } else if(num < 0){
		 System.out.println("Given number is a negative integer");
		 }
		 else {
		 System.out.println("Given number is ZERO");
		 }
		}

	}
