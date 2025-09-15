# Print-the-table-of-a-given-number
this program about the printing table of any number
import java.util.*;
class Test{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
         System.out.println("enter a number");
           int number= sc.nextInt();
           for(int i=1;i<=10;i++){
          int ans=number*i;
            System.out.println(number+" * "+i +" = "+ans);
            
           }
           System.out.println();
           }
           }
