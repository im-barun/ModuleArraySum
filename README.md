import java.util.*;
import java.lang.Math;


public class Adefy {
    public static void main(String[] args) 
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++)
        	arr[i]=sc.nextInt();
        int q=sc.nextInt();
        int[] brr=new int[q];
        for(int i=0;i<q;i++)
        	brr[i]=sc.nextInt();
        for(int i=0;i<q;i++)
        {
        	int sum=0;
        	for(int j=0;j<n;j++)
        	{
        		arr[j]=arr[j]+(brr[i]);
                sum+=Math.abs(arr[j]);
        	}
        	System.out.println(sum);
        }
        }
   }
