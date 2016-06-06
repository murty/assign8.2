import java.util.hashset.iterator();
public class plus {
   public static void main(String args[]) 
{
   HashSet <String> newset = new HashSet <String>();
   newset.add("I"); 
   newset.add("love");
   newset.add("writing");  
   newset.add("novels");
   Iterator iterator = newset.iterator(); 
   while (iterator.hasNext()){
   System.out.println( +iterator.next() + " ");  
   }
   }    
}
