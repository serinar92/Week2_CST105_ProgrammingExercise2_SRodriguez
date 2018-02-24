# Week2_CST105_ProgrammingExercise2_SRodriguez
import java.util.Scanner;

public class ProgrammingExercise2 {
        public static void main(String[] args) {
               //Prompt the user to enter a 
                int num = 30458;
                int sum = 0;
                while (num > 0) {
                    sum = sum + num % 10;
                    num = num / 10;
                }
                System.out.println(sum);
     
        }
    
}
