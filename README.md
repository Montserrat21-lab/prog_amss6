# prog_amss6
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package pilaas;

import java.util.Scanner;

/**
 *
 * @author sale7
 */
public class Pilaas {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic her
     Scanner sc=new Scanner(System.in);
     Pila pila = new Pila();
     //push agrega informacion
        int a = 1;
        pila.push(a);
        int b = 2;
        pila.push(b);
        int c =3;
        pila.push(c);
        int d =4;
        pila.push(d);
        int e=5;
        pila.push(e);
        int f=6;
        pila.push(f);
        int g=7;
        pila.push(g);
        int h=8;
        pila.push(h);
        int i=9;
        pila.push(i);
        int j=10;
        pila.push(j);
        int k=11;
        pila.push(k);
        int l=12;
        pila.push(l);
        int m=13;
        pila.push(m);
        int n=14;
        pila.push(n);
        int ñ=15;
        pila.push(ñ);
        int o=16;
        pila.push(o);
        int p=17;
        pila.push(p);
        int q=18;
        pila.push(q);
        int r=19;
        pila.push(r);
        int s=20;
        pila.push(s);
        int t=21;
        pila.push(t);
        int u=22;
        pila.push(u);
        int v=23;
        pila.push(v);
        int w=24;
        pila.push(w);
        int x=25;
        pila.push(x);
        int y=26;
        pila.push(y);
        int z=27;
        pila.push(z);
         int  opt , tope = 0, tam = 27;
    do{
             System.out.println("\n1-agregar\n"
             +"2-mostrar\n"
             + "3-eliminar\n");
             switch(opt=sc.nextInt()){
                 case 1:
                     if(tope >tam){
                     System.out.println("ingresa un valor");
                     tope++;
                     }else{System.out.println("pila llena..");}
                   break;
                  case 2:
                         if(tope<0){
                        for (i= tope-1 ; i >=0; i--){
                           System.out.print(" "+ pila );
                        }}else{System.out.println("pila vacia..");}
                  break;  
                  case 3: 
                         if(tope>0){
                         System.out.println(" dato eliminado...");
                         tope--;
                         }else{System.out.println("pila vacia no hay elementos `para ..");}
                 break;
             }
         }while(opt != 3);
 

}
}
    
    
    
