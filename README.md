# Accelerate
Accelerate Academy Projects
package Code;
import java.util.Scanner;
public class FullHouse {

    public static void main(String[] args) {
   	 Scanner input = new Scanner(System.in);
   	 System.out.println("Name a profession");
   	 String profession;
   	 profession = input.nextLine();
   	 
   	 System.out.println("Name a body part");
   	 String bodypart1;
   	 bodypart1 = input.nextLine();
   	 
   	 System.out.println("Name a verb. Be imaginative!");
   	 String verb1;
   	 verb1 = input.nextLine();
   	 
   	 System.out.println("Name another body part");
   	 String bodypart2;
   	 bodypart2 = input.nextLine();
   	 
   	 System.out.println("Name another verb. Be imaginative!");
   	 String verb2;
   	 verb2 = input.nextLine();
   	 
   	 System.out.println("Name an organ");
   	 String organ;
   	 organ = input.nextLine();
   	 
   	 System.out.println("Name your favorite destination!");
   	 String Destination;
   	 Destination = input.nextLine();
   	 
   	 System.out.println("What ever happened to predictability,\r\n" +
   			 "The "+profession+" the paperboy, the evening TV ,\r\n" +
   			 "Everywere you "+verb1+", \r\n" +
   			 "(Everywere you "+verb2+") \r\n" +
   			 "There's a "+organ+" \r\n" +
   			 "(There's a "+organ+") \r\n" +
   			 "A "+bodypart1+" to hold on to, \r\n" +
   			 "Everywere you "+verb1+", \r\n" +
   			 "(Everywere you "+verb2+") \r\n" +
   			 "There's a "+bodypart2+" of somebody who needs you, \r\n" +
   			 "When you're lost out there, \r\n" +
   			 "And you're all alone, \r\n" +
   			 "A light is waiting, \r\n" +
   			 "To carry you to"+Destination+" \r\n" +
   			 "Everywere you "+verb1+"");
    }

}
