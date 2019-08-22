import java.util.Scanner;

public class tripPlanner {
    public static void main(String[]args){
        greetings();
        budget();
        time();
        area();
    }

    public static void greetings(){
        Scanner input = new Scanner(System.in);
        System.out.println("Welcome to Vacation Planner!");
        System.out.print("What is your name? ");
        String name = input.nextLine();
        System.out.print("Nice to meet you "+name+", where are you travelling to? ");
        String place = input.next();
        System.out.println("Great! "+place+" City sounds like a great trip");
        System.out.println("**********");
        System.out.println();
    }

    public static void budget(){
        Scanner input = new Scanner(System.in);
        System.out.print("How many days are you going to spend travelling? ");
        int vacDays = input.nextInt();
        System.out.print("How much money, in USD, are you planning to spend on your trip? ");
        double vacBudget = input.nextDouble();
        System.out.print("What is the three letter currency symbol for your travel destination? ");
        String vacCurr = input.next();
        System.out.print("How many " + vacCurr + " are there in 1 USD? ");
        double vacConver = input.nextDouble();
        System.out.println();
        System.out.println("If you are travelling for " + vacDays + " days that is the same as " + (int)(vacDays*24) + " hours or " + (int)(vacDays*24*60) + " minutes.");
        System.out.println("If you are going to spend " + vacBudget + " EUR that means per day you can spend up to " + ((int)((vacBudget/vacDays) * 100)) / 100.0 + " USD.");
        System.out.println("Your total budget in " + vacCurr + " is " + ((int)((vacBudget*vacConver) * 100)) / 100.0 + " " + vacCurr + ", which per day is " + ((int)(((vacBudget*vacConver)/vacDays) * 100)) / 100.0 + " " + vacCurr);
        System.out.println("**********");
        System.out.println();
    }

    public static void time() {
        Scanner input = new Scanner(System.in);
        System.out.print("What is the time difference, in hours, between your home and your destination? ");
        int vacZone = input.nextInt();
        System.out.println("That means that when it is midnight at home it will be " + vacZone + ":00 in your travel destination and when it is noon at home it will be " + (int)(12+vacZone) + ":00.");
        System.out.println("**********");
        System.out.println();
    }

    public static void area() {
        Scanner input = new Scanner(System.in);
        System.out.print("What is the square area of your destination country in km2? ");
        double vacAreaKM = input.nextDouble();
        System.out.println("In miles2 that is " + ((int)((vacAreaKM*0.38610) * 100)) / 100.0);
        System.out.println("**********");
        System.out.println();
    }

}
