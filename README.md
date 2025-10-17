# javacode

import java.util.*;
class Club
{
    public static void main()
    {
        Scanner sc= new Scanner(System.in);
        int n,d,sum=0;
        System.out.println("Enter the number");
        n=sc.nextInt();
        while(n>0)
        {
            d=n%10;
            sum+=d;
        n=n/10;
    }
        System.out.println("Sum of the numbers="+sum);
    }
}
        
        
            
        
        
