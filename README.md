# Factorial-of-a-number-program
class Test { 
    // Method to find factorial 
    // of given number 
    static int factorial(int n) 
    { 
        int fact = 1, i; 
        for (i = 2; i <= n; i++) 
            fact *= i; 
        return fact; 
    } 
  
    // main method 
    public static void main(String[] args) 
    { 
        int num = 5; 
        System.out.println("Factorial of " + num + " is "
                           + factorial(5)); 
    } 
}
