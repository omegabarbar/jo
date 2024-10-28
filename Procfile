import java.util.Scanner;

    public class Main {
        public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
            System.out.print("Masukan jumlah tusuk sate: ");
            String input = scanner.nextLine();
        
            int[] tusukSate = { 6, 2, 5, 5, 4, 5, 6, 7, 6 };
            int totalTusuk = 0;
        
            for (char digit : input.toCharArray()) {
              totalTusuk += tusukSate[Character.getNumericValue(digit)];
            }
        
            System.out.println("Tusuk sate yang dibutuhkan budi adalah: " + totalTusuk);
          }
        }
