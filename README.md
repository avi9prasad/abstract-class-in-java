# abstract-class-in-java
abstract class Test  
{  
    static int i = 555;  
    static void TestMethod()  
    {  
        System.out.println("hi !! hello abhinav the coder !!");  
    }  
}  
public class TestClass extends Test   
{  
    public static void main (String args[])  
    {  
        Test.TestMethod();  
        System.out.println("i = "+Test.i);  
    }  
}  
