    import java.util.Scanner;

    public class ExercicioAula {

	public static void main(String[] args) {		
	
    //1) Escreva uma estrutura ENQUANTO de 7 a 77, em incrementos de 7
		
		 int cont; cont = 7;		  
		 while (cont <= 77) {
		     System.out.println(cont); cont = cont + 7; 
             }
		 

		
	//2) Escreva uma estrutura ENQUANTO de 20 a 2, em decrementos de 2
		 
         int i = 20;		 
		 while (i >= 2) { 
			 System.out.println(cont); cont = cont - 2; 
             }
		

		 
	// 3) Escreva uma estrutura PARA que imprima a seguinte sequência numérica: 99, 88, 77, 66, 55, 44, 33, 22, 11, 0

		 for (int contador = 99; contador >= 0; contador-=11) { 
			 System.out.println(contador); 
			 }


    // 4) Escreva uma estrutura PARA que imprima a seguinte sequência numérica: 2, 5, 8, 11, 14, 17, 20

        for (int conta = 2; conta <=20; conta +=3) {
            System.out.println(conta);
            }
