import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Taschenrechner");
        System.out.println("Bitte geben Sie die erste Zahl ein:");
        double zahl1 = scanner.nextDouble();
        System.out.println("Bitte geben Sie die zweite Zahl ein:");
        double zahl2 = scanner.nextDouble();
        System.out.println("Bitte geben Sie den Operator ein(+,-,*,/)");
        char operator = scanner.next().charAt(0);

        switch (operator) {
            case '+':
                double addition = zahl1 + zahl2;
                System.out.println("Ergebnis: " + addition);
                break;
            case '-':
                double subtraktion = zahl1 - zahl2;
                System.out.println("Ergebnis: " + subtraktion);
                break;
            case '*':
                double multiplikation = zahl1 * zahl2;
                System.out.println("Ergebnis: " + multiplikation);
                break;
            case '/':
                if (zahl1 == 0 || zahl2 == 0) {
                    System.out.println("Division durch 0 nicht möglich!");
                }
                else {
                    double division = zahl1 / zahl2;
                    System.out.println("Ergebnis: " + division);
                }
                break;
            default:
                System.out.println("Bitte einen gültigen Operator eingeben!");
                break;
        }
    }
}
