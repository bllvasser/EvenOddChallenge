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

