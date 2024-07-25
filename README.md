# IS-SORTED-OR-NOT
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
      int []a={1,2,3,4,5,6,7,8,87,95};
      int n=0;
      int k=0;
      for(int i=0;i<9;i++){
          if (a[i]>a[i+1]){
              n++;
          }
          else{
              n=0;
          }
          if(a[i]<a[i+1]){
               k++;
          }
          else{
             k=0;
          }
      }
      if (n==9 || k==9){
           System.out.println("Array in sorted order");
        }
        else{
             System.out.println("Array not in sorted order");
            
        }
    }
}
