# maps
import java.util.*; 
class map
 { 
   public static void main(String args[]) 
   {
      HashMap<Integer,String> x=new HashMap<Integer,String>(); 
      Scanner sc=new Scanner(System.in); 
      int n; 
      int key; 
      String value; 
      System.out.println("enter n value"); 
      n=sc.nextInt(); 
      for(int i=0;i<n;i++) 
      { 
        key=sc.nextInt(); 
        value=sc.next();
         x.put(key,value);
       } 
          System.out.println(x); 
          TreeMap<Integer,String> t=new TreeMap<Integer,String>(x);
          System.out.print(t);
     }
   }
