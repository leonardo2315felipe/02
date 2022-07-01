import java.util.Scanner;class Main {
  public static void main(String[] args) {
     Scanner input = new Scanner (System.in);

   int n1 = 4;
    int n2 = 5;

    System.out.println("digite o primeiro numero: ");
    int num1 = input.nextInt();
     
    System.out.println("digite o primeiro numero: ");
    int num2 = input.nextInt();

    if ((n1 % 2) == 0){
    System.out.println(n1 + "par");
    }else{
    System.out.println(n1 + "impar");
    }
    if((n2 % 2) ==0){
    System.out.println(n2 + "par");
    }else{
    System.out.println(n2+ "impar");
    if (( num1 % 2 ) == 0){
    System.out.println(num1 + "par");
    }else{
    System.out.println(num1 + "impar");
    }
    if((num2 % 2) == 0){
    System.out.println(num2 + "par");
    }else{
    System.out.println(num2 + "impar");
      
}
  }
}
}
