Java statements annotation
1.Annotate each Java statements with its statement types.
e.g., “x=y;” should become “x=y; //TYPE: assignment”

1.	“ int x;// TYPE: declaration”
2.	“ ( 4+10 ); // TYPE: additional expression”
3.	“i++;//TYPE: incrementation”
4.	“ i--;//Type: decrementation”
5.	“ if( x< 100 ){ System.out.println("x is  less than 100");}//TYPE : If statement”
6.	“
public class ReturnTypeAdd {
   public int add(int x, int y) { // with arguments
      int a = x+y;//declaration with assignment
      return a;
   }
   public static void main(String args[]) {
      ReturnTypeAdd= new ReturnTypeAdd();
      int add = test.add(15, 20);
      System.out.println("The sum of x and y is: " + add);
   }
}Type: Return statement 
”

7.	“if( a != 0)
{
   System.out.println (“a is not equal to zero”);
}
else
{
System.out.println (“a is equal to zero”);

} //Type: if-else statement”


8.	“if(b>0){
System.out.println(“b is a positive number” );
}
else if(b<0){
System.out.println(“b is a negative number” );
}else{ 
 System.out.println(“ b is neither positive nor negative number”);
}// Type:if-else-if statement
”

9.	“  public static void main(String[] args) {

    int number = 20;
    String size;

    // switch statement to check size
    switch (number) {

      case 15:
        size = "Smaller";
        break;

      case 25:
        size = "Medium";
        break;

      // match the value of number
      case 30:
        size = "Large";
        break;//

      case 35:
        size = " Largest";
        break;
      
      default:
        size = "Unknown";
        break;

    }
    System.out.println("Size: " + size);
  }//Type: switch statement”
 
10.	“ for( i=0; i<100; i++)//Type: for statement”

11.	”
class WhileLoopExample {
public static void main(String[] args) {
   System.out.println("Odd Numbers between 1 to 30 :");
   int i=1;
   while(i<=30){
     // If modulus of number after devision 2 is not equal to  0 then it is odd number
     if (i % 2 != 0) {
            System.out.println(i);
       }
      i++;
     }
   }
}Type: While loop statement”


12.	“public class ForEachLoopExample {
public static void main(String[] args) {
    //Declaring an array
    int numArray[]={0,1,2,3,4,5,6,7,8,9,10};
    //Print array by using for-each loop
    for(int i:numArray){
        System.out.println(i);
    }
}
}//Type: For-each loop statement

”

13.	 “  public class DoWhileLoopExample {
   public static void main(String[] args) {
    int i=1;
    System.out.println("Even numbers between 1 to 30:");
    do{
      if(i%2==0)
      {
      // If modulus of number after devision 2 is equal to  0 then even number
      System.out.println(i);
       }
      i++;
      while(i<=30);
}
} Type: Do-while loop statement”




 

