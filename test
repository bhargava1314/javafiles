import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;

public class FileLineCounter {

    public static void main(String[] args) {
        String filePath = "test.txt";  // file name

        int lineCount = 0;

        try {
            BufferedReader reader = new BufferedReader(new FileReader(filePath));

            while (reader.readLine() != null) {
                lineCount++;
            }

            reader.close();

            System.out.println("Total number of lines: " + lineCount);

        } catch (IOException e) {
            System.out.println("Error reading file: " + e.getMessage());
        }
    }
}
