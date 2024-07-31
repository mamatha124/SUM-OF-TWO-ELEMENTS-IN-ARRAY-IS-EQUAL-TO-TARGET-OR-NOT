# SUM-OF-TWO-ELEMENTS-IN-ARRAY-IS-EQUAL-TO-TARGET-OR-NOT 
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int l=sc.nextInt();
        int n[]=new int[l];
        System.out.print("Enter array: ");
        for(int i=0;i<l;i++){
            int k=sc.nextInt();
            n[i]=k;
        }
        System.out.println("Enter target:");
        int t=sc.nextInt();
        for(int i=0;i<l;i++){
            for(int j=i+1;j<l;j++){
                if(n[i]+n[j]==t){
                    System.out.println(n[i]+" + "+n[j]+" = "+t);
                    break;
                }
            }
        }
    }
}
