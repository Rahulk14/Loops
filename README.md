import java.util.*;
public class loop {
    public static void main(String[] args) {
        //for(int i = 0; i<11; i++){
            //System.out.print(i);
        //}
       // int i = 0;
        //while(i<11){
          //  System.out.print(i);
            //i++;
        //}
        //int i = 0;
        //do{
           // System.out.print(i);
            //i++;
        //}
       // while(i<11);
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();


        int sum = 0;
        for(int i = 0; i<=n; i++){
            sum = sum + i;
        }
        System.out.println(sum);

    }
}
