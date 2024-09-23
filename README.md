package  Atividade;


import java.util.*;


public class Atividade {
    public static void main(String[] args) {
    
    Scanner sc = new Scanner (System.in);
  
    System.out.print("Digite a temperatura em graus celsius");
    double celsius = sc.nextDouble();
    
    
    double fahrenheit = ((9 * celsius + 160/5));
    
    System.out.printf("A temperatura em Fahrenheit é:" +fahrenheit);

    
    
    sc.close();
    
    
    }
    
						}			
