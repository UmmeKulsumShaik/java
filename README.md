# java
class Student {
    String name;
    int age;

    public void getInfo() {
        System.out.println("The name of this Student is " + this.name);
        System.out.println("The age of this Student is " + this.age);
    }
}

 class OOPS {
        public static void main(String args[]) {
            Student s1 = new Student();
            s1.name = "Kulsum";
            s1.age = 19;
            s1.getInfo();

            Student s2 = new Student();
            s2.name = "Salma";
            s2.age = 18;
            s2.getInfo();
        }
    }
