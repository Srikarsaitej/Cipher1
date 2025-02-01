import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int Marks=sc.nextInt();
        if(Marks>=0 && Marks<=100){
            if(Marks>=90){
                System.out.println("Grade A");
            }
            else if(Marks>=80 && Marks<90){
                System.out.println("Grade B");
            }
            else if(Marks>=70 && Marks<80){
                System.out.println("Grade C");
            }
            else if(Marks>=60 && Marks<70){
                System.out.println("Grade D");
            }
            else{
                System.out.println("Grade F");
            }
        }
        else{
            System.out.println("Enter Marks Correctly");
        }
    }
}
