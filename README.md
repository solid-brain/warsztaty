import java.util.Scanner;

public class Zadanie {

    static Scanner sc = new Scanner(System.in);
    static String text = "exit";

    public static void main(String[] args) {

        System.out.println("Witaj świecie!");
        do {
            System.out.println("Aby zamknąć aplikację wpisz 'exit' i wciśnij klawisz ENTER");
        }
        while (!(getUserInput().equalsIgnoreCase(text)));
    }

    public static String getUserInput() {
        return sc.nextLine();
    }
}
