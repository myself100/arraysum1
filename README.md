package june2019;
import java.math.BigInteger;
import java.util.Scanner;
import java.util.*;
public class HelloWorld {
	public static void main(String[] args) {

		int a[]= {1,2,3,4,6,7,8,5};
		int sum=0;
		for(int i=0;i<a.length-1;i++) {
			sum=sum+a[i];
		}
		System.out.println(sum);
   }
}
