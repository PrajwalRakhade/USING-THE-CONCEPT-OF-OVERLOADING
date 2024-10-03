# USING-THE-CONCEPT-OF-OVERLOADING
 OVERLOAING IS VERY IMPORTANT CONCPT OF JAVA IN WHICH WE STUDY THAT HOW TO  USE SAME METHOD NAME FOR DIFFERENT METHODS
package check;
import java.util.Scanner;

class over{
	
	
	int  add(int x,int y) {
		return(x+y);
	}
	float  add(float x, float y) {
		return(x+y);
	}
}




 
public class Main {

	public static void main(String[] args) {
	over O=new over();
	System.out.println(O.add(22,45));
	System.out.println(O.add(33,76));
	

}
}
