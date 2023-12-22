import java.util.Scanner;
public class test {
    public static void main(String[] args) {
        int k;
        Scanner input = new Scanner(System.in);


        System.out.println("Sayı giriniz: ");
        k=input.nextInt();
        int i=1;
        while (i<=k){
            if(i%2==0){
                System.out.println(i);
            }
            i++;
        }


    }


}

