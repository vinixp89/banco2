# banco2

package bancoAlpha;

import java.util.Scanner;

public class secundaria {
public	int numConta;
 protected String tipo;
  private String dono;
  private int saldo;
  
  public int NumConta() {
	return numConta;
}
  Scanner entrada = new Scanner(System.in);
  
  
public void setNumConta(int numConta) {
	this.numConta = numConta;
}
public String getTipo() {
	return tipo;
}
public void setTipo(String tipo) {
	this.tipo = tipo;
}
public String getDono() {
	return dono;
}
public void setDono(String dono) {
	this.dono = dono;
}
public int getSaldo() {
	return saldo;
}
public void setSaldo(int saldo) {
	this.saldo = saldo;
}
public boolean isStatus() {
	return status;
}
public void setStatus(boolean status) {
	this.status = status;
}
private boolean status;
   
        
	   
	   
	   	public void exibeMenu(){
	        
	        System.out.println("\t Escolha a opção desejada");
	        System.out.println("1 - Criar conta");
	        System.out.println("2 - Saldo");
	        System.out.println("3 - Depositar");
	        System.out.println("3 - sacar");
	        System.out.println("pagar mensalidade");
	        System.out.println("4 - Sair\n");
	        System.out.print("Opção: ");
	    
	   
   }
   

   public void escolheOpcao(int opcao){
       double valor;
       
       switch( opcao ){
           case 1:    
                 abrirConta();
                   break;
                   
           case 2: 
        	   getSaldo();
        	       break;
        	       
        	       
           case 3:  
        	   depositar();
        	   break;
        	   
           case 4: 
        	   sacar();
        	   break;
           case 5: 
        	   pagarMensal();
        	   break;
        	   
       }
   }
   public void abrirConta() {}
   public void fecharConta(  ) { }
   public void depositar() { }
   public void sacar() {}
   public void pagarMensal() {}
  
   }
   
   
   
