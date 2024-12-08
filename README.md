# Ereditariet-
Prova di un esercizio 
import java.util.Scanner;

 // Compiler version JDK 11.0.2

 class Persona
 {  
   protected String nome;
   protected int eta;
   protected String nazione;
   public Persona (String nome,int eta,String nazione){
     this.nome = nome;
     this.eta = eta;
     this.nazione = nazione;
   }
 
}
class input extends Persona{
  public input (){
   super("",0,"");
   }
   public void sium(){
   
  Scanner scan = new Scanner(System.in);
  System.out.println("Inserisci il nome della persona");
  nome = scan.nextLine();
  System.out.println("Inserisci l'eta di "+nome);
  eta = scan.nexInt();
  if(eta<18){
   System.out.println("Il ragazzo è minorenne");
  }
  System.out.println("Inserisci la nazione di "+nome);
  nazione = scan.nextLine();
    }
  }
}  
public class main{
   public static void main(String args[])
   { 
      input in = new input();
      in.sium();
   }
 }
