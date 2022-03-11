package for_study;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class calc_1 {
	public static void calc(double inputNum1,double inputNum2,List<Double> list2) {
		list2.add(inputNum1+inputNum2);
		list2.add(inputNum1-inputNum2);
		list2.add(inputNum1*inputNum2);
		list2.add(inputNum1/inputNum2);
	}
	public static void addList1(List<Double> list1, double inputNum1,double inputNum2) {
		list1.add(inputNum1);
		list1.add(inputNum2);
	}
	public static void showInfo(List<Double> list2,int j) {
		for (Double i : list2) {
			switch(j) {
			case 1:
				System.out.print("a + b = ");
				j++;
				break;
			case 2:
				System.out.print("a - b = ");
				j++;
				break;
			case 3:
				System.out.print("a 곱하기 b = ");
				j++;
				break;
			case 4:
				System.out.print("a 나누기 b = ");
				j++;
				break;
			}
			System.out.println(i);
		}
	}
	
	public static void main(String[] args) { 
		Scanner sc = new Scanner(System.in);
		
		double inputNum1 = sc.nextDouble();
		double inputNum2 = sc.nextDouble();
		
		List<Double> list1 = new ArrayList<Double>();
		List<Double> list2 = new ArrayList<Double>();
		
		
		
		calc(inputNum1,inputNum2,list2);
		showInfo(list2,1);
		
		
}	
}	
	