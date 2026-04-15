import java.util.ArrayList;

public class TrainBogies {
public static void main(String[] args) {

        ArrayList<String> bogies = new ArrayList<>();

        bogies.add("Sleeper");
        bogies.add("AC Chair");
        bogies.add("First Class");

        System.out.println("Bogies after adding:");
        System.out.println(bogies);

        bogies.remove("AC Chair");

        System.out.println("Bogies after removing AC Chair:");
        System.out.println(bogies);

        if (bogies.contains("Sleeper")) {
            System.out.println("Sleeper bogie exists");
        } else {
            System.out.println("Sleeper bogie does not exist");
        }

        System.out.println("Final Bogies List:");
        System.out.println(bogies);
    }
