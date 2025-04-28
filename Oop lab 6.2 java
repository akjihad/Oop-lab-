interface Flyable {
    void fly();
}
class Bird implements Flyable {
    public void fly() {
        System.out.println("Bird is flying");
    }  
    void buildNest() {
        System.out.println("Bird is building a nest");
    }
}
class Airplane implements Flyable {
    public void fly() {
        System.out.println("Airplane is flying");
    }  
    void land() {
        System.out.println("Airplane is landing");
    }
}
public class Main {
    public static void main(String[] args) {
        Flyable[] flyables = { new Bird(), new Airplane() };      
        for (Flyable f : flyables) {
            f.fly();
        }   
        for (Flyable f : flyables) {
            if (f instanceof Bird) {
                Bird b = (Bird) f;
                b.buildNest();
            } else if (f instanceof Airplane) {
                Airplane a = (Airplane) f;
                a.land();
            }
        }
    }
}
