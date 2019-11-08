# DoArithmetic
import java.util.Scanner;

public class DoArithmetic {
	
public static void main(String [] args ) {

int fi, si, fn, pn, sn, rn, kn;

Scanner keyboard = new Scanner (System.in);


System.out.printf("Enter the two operands: ");
//enter 2 intergers
fi = keyboard.nextInt();
si = keyboard.nextInt();

fn = fi + si;
pn = fi - si;
sn = fi * si;
rn = fi / si;
kn = fi % si;



System.out.println(fi + " + " + si + " = " + fn);
System.out.println(fi + " - " + si + " = "+ pn);
System.out.println(fi + " * " + si + " = " + sn);
System.out.println(fi + " / " + si + " = " + rn);
System.out.println(fi + " % " + si + " = "+ kn);

}
}
