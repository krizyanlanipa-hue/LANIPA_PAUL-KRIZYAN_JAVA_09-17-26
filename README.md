# LANIPA_PAUL_KRIZYAN_JAVA_09-17-26
public class Main{ 
      public static void main(String[]args){
             System.out.prinln("Hello, World!")
             }
      }
//--DECLARING VARIABLES OF DIFF DATA TYPES--
//int-Whole Number
//double -double precision of decimal number
//float-single precision of decimal number
//char-single character(single quotes)
//boolean- true or false
//String- text of not primative

int     age        =    20      ;//WHOLE NUMBER
^        ^         ^     ^      ^
types  variable    EQ   value  close tag

double price = 40.55;//Double precision 
float weight = 85.9f// single precision using 'f'
char grade = 'A';// single character
Boolean isStudent = true;// True or False
String name = "Alice"; // Not Primative Text

//--Output usings Sytem.out.println---
System.out.println("Name: "+name);
System.out.println("Age: "+age);
System.out,println("Price: "+price)
System.out.println("Weight: "+weight);
System.out.println("Grade: "+grade);
System.out.println("Is Student: "+isStudent);

//---Getting input using Scanner---
import java.util.Scanner;
public class Main{
       public static void main(String[] args){
System.out.print(""\nEnter your city:);
String userCity =scanner.next();// reads one word(stops at whitespaces)
System.out.println("You Live in:" +userCity);

//---Reading a full line(including spaces)---
scanner.nextline();// clear leftover newline from previous next()
System.out.print("Enter a sentence about yourself");
String fullSentence = scanner.nextline();//read the entireline
System.out.println("You said: "+fullSentence);

scanner.close()
       }
     }
//Operators and Expression (+,-,*,/,<,>,=,!=||,&&)
public class Main{
       piblic static void main(String[]args){

       int a = 10, b = 3;
        System.out.println("a +b ="(a + b));
//output : a + b = 13
        System.out.println("a - b"(a - b));//
output: a - b = 7
         System.out.println("a * b"(a * b));//
output: a * b = 30
         System.out.println("a / b"(a / b));//output a / b = 3
         System.out.println("a % b ="(a % b));//
output a % b = 1

double x = 10, y =3;
System.out.println("x / y  ="(x / y));//output x /
y = 3.33333335
