import java.util.Scanner;

public class MirrorPattern {

	public static void main(String[] args) {

		Scanner input = new Scanner(System.in);
		System.out.println("enter number upto you want to generate mirror pattern:");
		int limit = input.nextInt();// let's input is 10
		int temp, temp1;
		for(int i=0;i<limit;i++) {
			temp=limit;
			while(temp>=0 ) {
				if(temp <= i)
					System.out.print(temp +" ");
				else
					System.out.print("  ");
				temp--;
			}
			temp=1;
			while(temp<=i ) {
					System.out.print(temp+" ");
				temp++;
			}
			System.out.println();
		}
	}

}
/*
output would be:
                        0 
                      1 0 1 
                    2 1 0 1 2 
                  3 2 1 0 1 2 3 
                4 3 2 1 0 1 2 3 4 
              5 4 3 2 1 0 1 2 3 4 5 
            6 5 4 3 2 1 0 1 2 3 4 5 6 
          7 6 5 4 3 2 1 0 1 2 3 4 5 6 7 
        8 7 6 5 4 3 2 1 0 1 2 3 4 5 6 7 8 
      9 8 7 6 5 4 3 2 1 0 1 2 3 4 5 6 7 8 9
*/
