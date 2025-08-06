# Assignment-08-java
<div style="overflow-x:auto;">
<pre>
<code>
//Assignment no:08
//Logical AND

import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        System.out.println("1.Have you Completed your master?");
        char word=sc.next().charAt(0);
        
        System.out.println("2.Are you fluent in English?");
        char secondWord=sc.next().charAt(0);
        if(word=='y' && secondWord=='y'){
            System.out.println("--WELCOME--");
            System.out.println("You are Eligible for job interview!");
       } else if(word=='y' && secondWord=='n'){
            System.out.println("You are not  Eligible for job interview!");
            System.out.println("---You have to learn English!--");
       }
       else if(word=='n' && secondWord=='y'){
            System.out.println("You are not Eligible for job interview!");
            System.out.println("--- Complete you master--!");
       }
       else if(word=='n' && secondWord=='n'){
            System.out.println("Sorry You Are Not Eligible for job Interview!");
            System.out.println("You have to learn both!");
        }else{
            System.out.println("Please click only y/n");
        }
        
    }
}
</code>
</pre>
</div>
