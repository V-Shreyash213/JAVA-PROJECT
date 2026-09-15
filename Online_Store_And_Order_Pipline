import java.util.Scanner;
public class Online_Store_And_Order_Pipline {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        int n = 1;
        System.out.println("Type your order in this order");
        System.out.println("product name");
        System.out.println("Product price");
        System.out.println("Product quantity");
        while (true) {
            String [] cart = new String [n];
            for(int i =0;i<n;i++){
                cart[i] = input.nextLine();
            }
            double [] prices = new double[n];
            for(int i=0;i<n;i++){
                prices[i]=input.nextInt();
            }
            double [] quantity=new double [n];
            for(int i=0;i<n;i++){
                quantity[i] = input.nextDouble();
            }
            System.out.println("Do you still want to continue: ");
            input.nextLine();
            String continue_Shopping = input.nextLine();
            if (continue_Shopping=="yes"){
                n++;
            }
            else break;
        }
        
    }
    static double[] Total_Cost(int n,double[] prices,double[] quantity){
        double[] t = new double[n];
        for (int i =1;i<n;i++){
            t[i] = quantity[i]*prices[i];
        }
        return t;
    }
}
