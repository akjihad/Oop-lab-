import java.util.Scanner;
class rectangle {
    double length;
    double width;
    rectangle(double length, double width) {
        this.length = length;
        this.width = width;
    }
    double calculateArea() {
        return length * width;
    }
    double calculatePerimeter() {
        return 2 * (length + width);
    }
}
class circle {
    double radius;
    circle(double radius) {
        this.radius = radius;
    }
    double calculateArea() {
        return 3.1416 * (radius * radius);
    }
    double calculatePerimeter() {
        return 2 * 3.1416 * radius;
    }
}
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the length of the rectangle: ");
        double Length = scanner.nextDouble();
        System.out.print("Enter the width of the rectangle: ");
        double Width = scanner.nextDouble();
        rectangle rect = new rectangle(Length, Width);
        System.out.println("Rectangle Area: " + rect.calculateArea());
        System.out.println("Rectangle Perimeter: " + rect.calculatePerimeter());
        System.out.print("Enter the radius of the circle: ");
        double r = scanner.nextDouble();
        circle circle = new circle(r);
        System.out.println("Circle Area: " + circle.calculateArea());
        System.out.println("Circle Perimeter: " + circle.calculatePerimeter());
    }
}
