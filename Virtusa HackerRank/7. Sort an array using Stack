import java.io.*;
import java.util.*;

public class Main
{
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int n = sc.nextInt();
		Stack<Integer> stack1 = new Stack<Integer>();            
		for(int i=0;i<n;i++)
		{
		    stack1.push(sc.nextInt());
		}
		
		Stack<Integer> stack2 = new Stack<Integer>();
        while(!stack1.isEmpty()) 
        { 
            int var = stack1.pop();       
            while(!stack2.isEmpty() && stack2.peek()>var)               
            { 
            stack1.push(stack2.pop()); 
            } 
            stack2.push(var); 
        } 
        String s="";
		for(int i:stack2){
		    s+=i+" ";
		}
		System.out.println(s);
	}
}


/*

INPUT:
7
8 5 7 1 9 12 10

OUTPUT:
1 5 7 8 9 10 12

*/
