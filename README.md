# Exceptions 
class Ex1
{
    public static void main(String args[])
    {
        try
        {
            int a=10; 
            int b=0; // can't divide by zero so here we have to change the value
           int c=a/b;

           System.out.println("The Addtion is:"+c);
        }
        catch(ArithmeticException e)
        {
            System.out.println(e);
        }
        System.out.println("Out of the Block!");
    }
}
