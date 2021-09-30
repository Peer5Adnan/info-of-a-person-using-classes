# info-of-a-person-using-classes
import java.util.Scanner;
public class Person {
    String name;
    int age;
    double marks;
    char grade;
}
class Personinfo{
public static void main(String args[]) {
    Person one = new Person();
    System.out.println("enter the info of about a person");
    one.name = "adil";
    one.age = 21;
    one.marks = 70.5;
    one.grade = 'b';
    System.out.println("the info of a person is  " + one.name + "\n," + one.age + "\n," + one.marks + "\n," + one.grade);
}
}
