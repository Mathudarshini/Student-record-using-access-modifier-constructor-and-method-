
class Student {
private String name;
private int rollNo;
private double marks;

public Student(String name, int rollNo, double marks) {
    this.name = name;
    this.rollNo = rollNo;
    this.marks = marks;
}

public void displayDetails() {
    System.out.println("Name: " + name);
    System.out.println("Roll No: " + rollNo);
    System.out.println("Marks: " + marks);
}

public void updateMarks(double newMarks) {
    marks = newMarks;
}

public double getMarks() {
    return marks;
}

}

public class Main {
public static void main(String[] args) {
Student student1 = new Student("John Doe", 101, 85.5);
student1.displayDetails();

   student1.updateMarks(90.0);
    System.out.println("Updated Marks: " + student1.getMarks());
}

}



Output:

Name: John Doe
Roll No: 101
Marks: 85.5
Updated Marks: 90.0
# Student-record-using-access-modifier-constructor-and-method-
