import java.util.Scanner;

public class Main1 {
    public static void main (String[] args) {
        Scanner scanner = new Scanner(System.in);
        double ch = scanner.nextDouble();
        if (ch>=0 & ch<10){
            System.out.println("DIGIT");
        }
        else if (ch>9 & ch<100) {
            System.out.println("NUM");
        }
        else {
            System.out.println("OTHER");
        }
    }
}
