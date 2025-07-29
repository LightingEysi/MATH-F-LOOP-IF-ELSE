public class Main {
    public static void main(String[] args) {
//even        
        for ( int i = 2; i <= 10; i += 2){
          System.out.println("Even: " + i);
        }
        System.out.println();

//odd        
        for ( int i = 1; i <= 10; i += 2){
            System.out.println("Odd: " + i);
        }
        System.out.println();
//sum 
        int sum = 0;
        for ( int i = 1; i <= 5; i++){
            sum += i;
        System.out.println("Sum :" + sum);    
        }
        System.out.println();

//Reverse        
         for ( int i = 5; i >= 1; i--){
             System.out.println("Reverse: " + i);
         }
         System.out.println();
         
//Arithmetic-operations
         String[] math = {"Addition", "Subtraction", "Multiplication", "Division"};
         
         for ( int i = 0; i < math.length; i++){
             System.out.println("Operator: " + math[i]);
         }
         System.out.println();

//Multiplication-Table
         for ( int i = 1; i <= 3; i++){
             System.out.println("Multiplication Table of: " + i);
         for ( int j = 1; j <= 10; j++){
             System.out.println(i + " x " + j + " = " + (i * j));
         }
    }     
         System.out.println();
         
//Calculator         
        double num1 = 10;
        double num2 = 5;
        char operator = '+'; // Choose a type of calculation +,-,*,/

        double result;

        if (operator == '+') {
            result = num1 + num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '-') {
            result = num1 - num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '*') {
            result = num1 * num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '/') {
            result = num1 / num2;
            System.out.println("Result: " + result);
            
        } else {
            System.out.println("Invalid operator! Please use + or -");
         
        } 
    }
}    
