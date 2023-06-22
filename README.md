# Experiment-7

# Inheritance

## Aim:
  To write a Java program using inheritance and Properties one class can acquire the properties of others.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Employee" and create required statements.

Step 3 : Create a another class called "Manager" and create required statements.

Step 3 : Create another class,called the "Member" and create required statements

Step 4 : Create a main class,called the "Solution".

Step 5 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 6 : Display the statements from the first and secomd Class using Solution Class in the terminal.

## Program
```

public class Employee extends Member {
    public String specialization;
}
public class Manager extends Member {
    public String departemnt;
}
public class Member {
    public String name;
    public int age;
    public String ph;
    public String address;
    public String sal;
    public void dissal() {
        System.out.println("The Salary of this employee is: " + sal);
    }
}
public class temp {
    public static void main(String[] args) {
        Employee emp1 = new Employee();
        Manager emp2 = new Manager();
        emp1.name = "BALA";
        emp1.age = 19;
        emp1.ph = "636987566";
        emp1.address = "cuddalore";
        emp1.sal = "40k";
        emp2.departemnt = "AI-DS";
        emp1.specialization = "data science";
        System.out.println(emp1.name + "\n" + emp1.age + "\n" + emp1.ph + "\n" + emp1.address + "\n" + emp1.specialization + "\n" + emp2.departemnt);
        emp1.dissal();

    }
}
```

## Output
![image](https://github.com/balaji-21005757/Experiment-8/assets/94372294/4541be84-de99-4896-b9ae-c06492b260a6)


## Result 
  We have successfully created a Java program using inheritance one class can acquire the properties of others.
