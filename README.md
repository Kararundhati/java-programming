# java-programming
Factorial of a number

import java.util.*;
import java.lang.*;
import java.io.*;

// Name of the class has to be "Main" only if the class is public. //
class fact
{
	static int factorial(int n){
		if(n==0)
		return 1;
		else
return(n*factorial(n-1));
}
	public static void main (String[] args) throws java.lang.Exception
	{
		int i,n,f=1;
		Scanner s=new Scanner(System.in);
		n=s.nextInt();
		f=factorial(n);
		
		System.out.println("factorial of num is"+f);
	}

}

