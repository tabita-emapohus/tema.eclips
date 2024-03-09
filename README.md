import java.util.Scanner;

public class Main2 {

	public static void main(String[] args) {
		 Scanner scanner = new Scanner(System.in);
	          //int x = scanner.nextInt();
	          /*Problema 1
	        if (x > 5) {
	            System.out.println("ADMIS");
	        }else {
	            System.out.println("RESPINS");
	        
	        	if (x < 1 && x > 10) {
	            System.out.println("INVALID");
	        } 
	        }*/
	 //Problema 2
	        /*String numarlitera="";
	        if(x >= 1 && x<= 5 ) {
	        	switch(x) {
	        	case 1:
	        		numarlitera="UNU";
	        		break;
	        	case 2:
	        		numarlitera="DOI";
	        		break;
	        	case 3:
	        		numarlitera="TREI";
	        		break;
	        	case 4:
	        		numarlitera="PATRU";
	        		break;
	        	case 5:
	        		numarlitera="CINCI";
	        		break;
	        		default:
	        			break;
	        	}
	        	System.out.println("Numarul " + x +  " este " + numarlitera);
	        }
	        else
	        {
	        	System.out.println("INVALID");
	        }*/
	 //Problema 3
	          //int y = scanner.nextInt();
	          /*if(x % 2 == 0 && y % 2 == 0) {
	        	  System.out.println((x + y )/2);
	          }
	          else {
	        	  if(x % 2 == 1 && y % 2 == 1) {
	        		  System.out.println(x * y);
	        	  }
	        	  else {
	        		  if(x % 2 == 0 && y % 2 == 1 || x % 2 == 1 && y % 2 == 0) {
	        			  System.out.println(x + y);
	        		  }
	        	  }
	          }*/
	    //Problema 4
	          //int z = scanner.nextInt();
	         /* if(x < y && x < z) {
	        	  System.out.println(x);
	          }
	          else {
	        	  if(y < x && y < z) {
	        		  System.out.println(y);
	        	  }
	        	  else {
	        		  if(z < x && z < y) {
	        			  System.out.println(z);
	        		  }
	        	  }
	          }*/
	    // Problema 5 
	          
	          /*int s=0;
	          int i;
	          for( i = 1; i <= x; i++) {
	        	  s = s + i*2;
	          }
	          
	          System.out.println(s);
	          */
	     
	          // Problema 6
	          
	          /*int s=0;
	          int i;
	          for( i = 1; i <= 2* x-1; i = i + 2) {
	        	  s = s +i;
	          }
	          System.out.println(s);
	          */
	   //Problema 7 
	          /*int s=0;
	          int i;
	          float ma=0;
	          for( i = 0; i <= x; i++) {
	        	  s = s + i;
	          }
	          ma = s / x;
	          
	          System.out.println(ma);
	          */
	   //Problema 8
	          /*int FACT=1;
	          int i;
	          for( i = 1; i <= x; i++) {
	        	  FACT = FACT * i;
	          }
	          System.out.println(FACT);
	          */
	   //Problema 9
	          /*boolean prim;
	          prim = true;
	          int i;
	          if(x <= 1) {
	        	  prim = false;
	          }
	          for(i = 2; i <= x-1; i++) {
	        	  if(x % i == 0) {
	        		  prim = false;
	        	  }
	          }
	          if(prim == true) {
	        	  System.out.println("PRIM");
	          }
	          else {
	        	  System.out.println("NU E PRIM");
	          }
	          */
	   //Problema 11
	          /* int i;
	          for(i = 1; i<= x; i++) {
	        	  if(x % i == 0) {
	        		  System.out.println(i);
	        	  }
	          }
	            */ 
	     //Problema 13 
		 /*int a;
		 int b;
		 
		 for(a = 17; a < 1000; a = a + 17) {
			 for(b = 19; b< 1000; b = b + 19) {
				 if(a + b == 1000) {
					 System.out.println("Perechea " + a + ", " + b);
			        }
				 }
			 }*/
    // Problema 14 
		 
		 /*int a;
		 int b;
		 
		 for(a = 17; a < 1000; a = a + 17) {
			 for(b = 19; b< 1000; b = b + 19) {
			  if((a % 17 == 0 || a % 13 == 0) && (b % 19 == 0 || b % 7 == 0)) {
				  if(a + b == 1000) {
					  System.out.println("Perechea " + a + ", " + b);
				  }
			  }
			 }
		 }*/
     //Problema 15
		 /*int x;
		 int a;
		 int b;
		 for(a =0; a <= 9; a++) {
			 for(b = 0; b <= 9; b++) {
				 x = 3000 + a* 100 + 20 +b;
				 if(x % 9 == 0) {
					 System.out.println(x);
				 }
			 }
		 }*/
       //Problema 16
		/* int x = scanner.nextInt();
		 int nrcif;
		 nrcif=0;
		 while(x != 0) {
			 nrcif = x % 10;
			 System.out.print( nrcif);
			 x = x/10;
		 }
		 */
      //Problema 17 
		 /*int x = scanner.nextInt();
		 int max; 
		 int c;
		 c = 0;
		 max = 0;
		 while(x > 0) {
			 c = x % 10;
			 if(c > max) {
				 max = c;
			 }
			 x = x / 10;
		 }
		 System.out.println(max);*/
		 
    


	 
 
  
