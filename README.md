# 20201230


package basic;

import java.util.Scanner;

public class CodeUp1556 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		CodeUp1556 m=new CodeUp1556();
		System.out.println(m.f());
	}
	int f() {
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int x=1;
		for (int i = n; i >= 1; i--) {
			x*=i;
		}
		return x;
	}
}
