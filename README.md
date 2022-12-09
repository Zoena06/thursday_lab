# thursday_lab
Q1)Write a program to accept your basic details (Name, No, Gmail, Address ,gender, percentage ) from user and display the output  
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Scanner sc = new Scanner(System.in);                //Taking input for print detail
        System.out.println("Please Enter Following Detail.....");
        System.out.println("Name : ");
        String name = sc.next();
@@ -16,7 +16,7 @@ public static void main(String[] args) {
        String Add = sc.next();
        System.out.println("Enter Percentage : ");
        double percent = sc.nextDouble();

                                                        //Here we are printing the given detail
        System.out.println("Hello "+name+", Your percentage is : "+percent+"your number is "+no+" Your Gmail is : "+mail+"And you are from : "+Add);
    }
}
