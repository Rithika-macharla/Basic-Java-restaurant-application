import java.util.*;

public class orders {

    public static void main(String[] args){
        System.out.println("Welcome to CMR restaurant!!");
        System.out.println("Hi, ENter your name:");
        Scanner or=new Scanner(System.in);
        String name=or.nextLine();
        System.out.println("Hey "+name+ ", What do you like to order?");
        System.out.println("1. Dal fry - 40\n2. Paneer butter masala - 100\n3. Chicken curry - 120\n4. fish fry - 100\n5. tomato curry - 30\n Select from the menu");
        int order;
        order= or.nextInt();
        System.out.println("Please Enter the quantity:");
        int q=or.nextInt();
        String dish=" ";
        int rate=0;
        switch(order){
            case 1:
            dish="Dal Fry";
            rate=40;
            break;
            case 2:
            dish="Paneer butter masala";
            rate=100;
            break;
            case 3:
            dish="Chicken curry";
            rate=120;
            break;
            case 4:
            dish="Fish fry";
            rate=100;
            case 5:
            dish="Tomato curry";
            rate=30;
            break;
            default:
            System.out.println("Invalid response.");
        }
        System.out.println("You selected "+dish+", pay "+(q*rate));
        int r=or.nextInt();
        if(r==q*rate){
            System.out.println("Order is taken please kindly wait.");
        }
        else
        System.out.println("Invalid amount");
    }
}
