# oopsinjava
I have make a programe to make your own data type in java using oops.
package oops;

public class StudentClass {
    // create new data type
    public static class Student {
        String name;
        int rno;
        double percent;
    }

    public static void main(String[] args) {
        Student x = new Student();
        x.name = "Tisha";
        x.rno = 78;
        x.percent = 97.8;
        System.out.println(x.name);
    }
}

