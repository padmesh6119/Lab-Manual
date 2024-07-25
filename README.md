
import java.util.Scanner;
class Student{
    int rollno;
    String name;
}
public class Main{
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    Student s =new Student ();
    s.rollno=sc.nextInt();
    sc.nextLine();
    s.name = sc.nextLine();
    System.out.print(s.rollno+" "+s.name);
  }
}
