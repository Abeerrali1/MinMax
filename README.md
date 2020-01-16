# MinMax
Just a simple code written on java to show the maximum number
public static int Maximum (int a, int b)
    {
        System.out.print("The Maximum is:");
        if (a>b)
        {
            return a;
        }
        else{
       return b;
    }
    }
 
 
    public static void main (String[] args)
    {
 
        Scanner input = new Scanner(System.in);
 
        int num1;
        int num2;
 
        System.out.print("Enter first number: ");
        num1 = input.nextInt();
 
        System.out.print("Enter second number: ");
        num2 = input.nextInt();
 
        System.out.print("The max is: "+ Maximum(num1, num2) +"\n");
 
    }
 
