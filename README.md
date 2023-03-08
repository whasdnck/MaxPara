# MaxPara


## MaxPara 코드
package sungil21102algo;

public class MaxPara {

	static int maxpara(int a, int b, int c) {
		int max = a;
		if (b > max)
			max = b;
		if (c > max)
			max = c;
			
			return max;
	}
	
	public static void main(String[] args) {

		System.out.println("maxpara(10,9,8)" + maxpara(10,9,8));
		System.out.println("maxpara(5,15,2)" + maxpara(5,15,2));
	}

}
