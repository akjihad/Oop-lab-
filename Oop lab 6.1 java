class Person {
    void display() {
        System.out.println("I am a Person");
    }
}
class Student extends Person {
    void study() {
        System.out.println("Student is studying");
    }
}
public class Main {
    public static void main(String[] args) {
        Person p = new Student();
        p.display();
        Student s = (Student) p;
        s.study();
    }
}
