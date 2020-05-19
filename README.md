# Queue-
This is a sample coding I had done in my class
public class QueueDemo
{
    public static void main(String args[])
    {
        Queue fruitQ = new Queue();
        
        fruitQ.enqueue ("\nkiwi");
        fruitQ.enqueue ("\napple");
        fruitQ.enqueue ("\nbanana");
        fruitQ.enqueue ("\ndurian");
        
        fruitQ.print();
        
        System.out.println("\nFirst element : " + fruitQ.getFront().toString()+"\n");
        
        System.out.println("\nLast element : " + fruitQ.getEnd().toString()+"\n");
    }
    
}
        
        
