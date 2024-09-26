# factorial using recursive function
import java.util.*;
public class Main
{
    public static int fact(int n){
        if(n==0){
            return 1;
        }
        else{
             return n*fact(n-1);
           
        }
    
    }
	public static void main(String[] args) {
	    int num=4;
	    int f= fact(num);
		System.out.println(f);
	}
}
