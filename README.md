# Prashant/* Program to print 2,4,8,32..... */

import java.util.*;
import java.lang.*;
import java.io.*;
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// /in this we need to multiply last two numbers to get next number  
		int a=1,b=2,c;
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();
		for(int i=1;i<=n;i++){
			c=a*b;
			a=b; //Dwaping of numbers
			b=c;
			System.out.print(" "+c);
		}
	}
}
