# Weekly-activities-
Object oriented programming 
class CoffeeOrder {
    String size;
    double price;

    // Constructor
    CoffeeOrder(String size, double price) {
        this.size = size;
        this.price = price;
    }
}

public class Main {
    public static void main(String[] args) {
        // Create two objects
        CoffeeOrder order1 = new CoffeeOrder("Large", 250.0);
        CoffeeOrder order2 = new CoffeeOrder("Medium", 150.0);

        // Display details
        System.out.println("Order 1: Size = " + order1.size + ", Price = " + order1.price);
        System.out.println("Order 2: Size = " + order2.size + ", Price = " + order2.price);
    }
}
