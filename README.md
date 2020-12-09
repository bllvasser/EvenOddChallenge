# EvenOddChallenge
package academy.learnprogrmming;

public class Main {

    public static void main(String[] args) {

        isEvenNumber(5);
        isEvenNumber(4);
        
    }
    public static boolean isEvenNumber(int number){
        if(number % 2 == 0) {
            System.out.println("It is an even number");
            return true;
        }
        System.out.println("It is an odd number");
        return false;
    }
}
"C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=50280:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\ForLoopExercises\out\production\ForLoopExercises academy.learnprogrmming.Main
It is an odd number
It is an even number

Process finished with exit code 0

package academy.learnprogrmming;

public class Main {

    public static void main(String[] args) {



        int number = 4;
        int finishNumber = 20;
        int evenNumbersFound = 0;

        while(number <= finishNumber) {
            number++;
            if(!isEvenNumber(number)) {
                continue;
            }
            System.out.println("Even number is " + number);
            evenNumbersFound++;

            System.out.println("Total number of even numbers is " + evenNumbersFound);
            if(evenNumbersFound == 5) {
                break;
            }

        }

    }
    
    "C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=50463:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\ForLoopExercises\out\production\ForLoopExercises academy.learnprogrmming.Main
Even number is 6
Total number of even numbers is 1
Even number is 8
Total number of even numbers is 2
Even number is 10
Total number of even numbers is 3
Even number is 12
Total number of even numbers is 4
Even number is 14
Total number of even numbers is 5

Process finished with exit code 0

