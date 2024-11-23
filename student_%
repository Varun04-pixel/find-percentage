import java.util.Scanner;

public class problems {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter science marks: ");
        float a1 = sc.nextFloat();
        System.out.print("Enter maths marks: ");
        float a2 = sc.nextFloat();
        System.out.print("Enter english marks: ");
        float a3 = sc.nextFloat();
        float total = ((a1+a2+a3)/300)*100f;
        if (a1 >= 33 && a2 >= 33 && a3 >= 33) {
            if (total >= 40) {
                System.out.println("Passed the exam = " + total + "%");
            } else {
                System.out.println("Failed the exam = " + total + "%");
            }
        } else if (total >= 40) {
            if (a1 < 33) {
                System.out.print("Failed in science with " + a1 + " marks, ");
            }
            if (a2 < 33) {
                System.out.print("Failed in maths with " + a2 + " marks, ");
            }
            if (a3 < 33) {
                System.out.print("Failed in english with " + a3 + " marks, ");
            }
            System.out.println("But passed the exam with " + total + "%");
        } else {
            System.out.println("Failed the exam with " + total + "%");
        }
    }
}
