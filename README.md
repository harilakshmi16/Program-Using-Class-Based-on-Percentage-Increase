# Program-Using-Class-Based-on-Percentage-Increase
Program Using Class Based on Percentage Increase

class PercentageIncrease {
    double calculateIncrease(double original, double increase) {
        return original + (original * increase / 100);
    }
}

public class PercentageIncreaseExample {
    public static void main(String[] args) {
        PercentageIncrease calc = new PercentageIncrease();
        double original = 1000;
        double increase = 10;

        double result = calc.calculateIncrease(original, increase);
        System.out.println("New value after " + increase + "% increase: " + result);
    }
}

Output

New value after 10% increase: 1100.0
