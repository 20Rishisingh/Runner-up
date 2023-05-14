/*
Three numbers A, B and C are the inputs. Write a program to find second largest among them.

        "Sample Input"
         120 11 400

        "Sample Output"
         120
*/



import java.io.*;
import java.util.*;

public class Solution {
    public static void main(String[] args) {
  
    Scanner asd = new Scanner(System.in);
    int a = asd.nextInt();
    int b = asd.nextInt();
    int c = asd.nextInt();

        if (a>b){
            if (b>c){
                System.out.println(b);
            }
            else {
                System.out.println(a);    
            }
        }
        else {
            if (b>c){
               if (c>a){
                       System.out.println(c);
               }
                else {
                    System.out.println(a);
                }
            }
            else {
                System.out.println(b);
            }
        }      
    }
}
