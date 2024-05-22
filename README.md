# Fraction-Class
The Fraction Class in Java represents a mathematical fraction with a numerator and a denominator. It includes various methods for performing common mathematical operations on fractions, such as addition, subtraction, multiplication, division, and reduction. 

# Usage Example

    public class Main{
      public static void main(String[] args){
        // Create fractions
        Fraction f1 = new Fraction(1, 2);
        Fraction f2 = new Fraction(1, 3);
        
        // Perform operations
        Fraction sum = Fraction.add(f1, f2);
        Fraction difference = Fraction.subtract(f1, f2);
        Fraction product = Fraction.multiply(f1, f2);
        Fraction quotient = Fraction.divide(f1, f2);

        // Print results
        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
        System.out.println("Quotient: " + quotient);
    }}
