public class Division {

    public static void main(String[] args)
    {
        Scanner scan = new Scanner(System.in);

        System.out.print("Enter an integer: ");
        int input= scan.nextInt();

        int one = (input/100);
        int two = (input % 100);
        int three = (input % 100) %10;
        int four = (input % 100) /10;
        int five = (input % 1000) /100;
        int six = (input/1000);
        System.out.println(input/100.0);

        System.out.println(two);
        System.out.println(one);
        System.out.println(three + "" + four + "" + five + "" + six);

    }
}
