
package arraypackage;

import java.util.Scanner;
public class NewClass6 {
 
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int [][] A=new int [3][3];
      int [][] B=new int [3][3];
        System.out.println(" A =");
        for (int i = 0; i < 3; i++) {
           // System.out.println(" ");
            
            for (int j = 0; j < 3; j++) {
                 System.out.printf("A[%d][%d] =",i,j);
                A[i][j]=input.nextInt();
         
                
        
            }
        }  System.out.println("A=");
        for (int i = 0; i < 3; i++) {
           // System.out.println(" ");
            
            for (int j = 0; j < 3; j++) {
               // System.out.printf("A[%d][%d] =",i,j);
                System.out.print("\t\t  "+A[i][j]);
            
            }
            
         System.out.println(" ");
        }
        System.out.println("B =");
        
        for (int i = 0; i < 3; i++) {
          
            for (int j = 0; j < 3; j++) {
                System.out.printf("B[%d][%d] =",i,j);
            B[i][j]=input.nextInt();      
            }
            
        }
 System.out.println("B=");
        for (int i = 0; i < 3; i++) {
            
            for (int j = 0; j < 3; j++) {
                System.out.print("\t \t  "+B[i][j]);
            }
            System.out.println(" ");
            
                
            }
        System.out.println("A+B= ");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                System.out.print("  \t \t "+(A[i][j]+B[i][j]));
            }
            System.out.println(" ");
        }
        }
      
    }




