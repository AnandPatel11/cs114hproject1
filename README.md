# cs114hproject1
#https://www.chegg.com/homework-help/questions-and-answers/assignment-create-maze-abstract-data-type-program-read-display-traverse-mazes-characters---q73683012?cs_resub=1
package maze;
import java.util.*;
import java.io.*;
public class maze1 {

	public static void main(String args[])
	{
		
		System.out.println("hi");
		try {

            File f = new File("C:\\Users\\anp8\\Downloads\\samp.dat.txt");

            BufferedReader b = new BufferedReader(new FileReader(f));

            String readLine = "";

            System.out.println("Reading file using Buffered Reader");

            while ((readLine = b.readLine()) != null) {
                System.out.println(readLine);
            }

        } catch (IOException e) {
            e.printStackTrace();
        }
	
	}
}
