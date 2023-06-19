# Student detail
package com.project;

import java.io.File;
import java.util.Scanner;

public class Word {
	public static void main(String[] args)
	{
		System.out.println("name,roll,CGPA,email");
		for(int i=1;i<=5;i++)
		{
		Scanner a=new Scanner(System.in);
		System.out.println("S no=" +i);
	    String name=a.nextLine();
		int roll=a.nextInt();
		double CGPA=a.nextDouble();
		Scanner b=new Scanner(System.in);
		String email=b.nextLine();
		System.out.println("student details: " +name +"," +roll +"," +CGPA +"," +email );
		}
		System.out.println("File path: " + new File("Word").getAbsolutePath());
	}
}
