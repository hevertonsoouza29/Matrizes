# Matrizes
matrizes Tridimensionais 
 package Matrizes;

public class MatrizTridimensional {

	public static void main(String[] args) {
		
		int [] [] [] matrizTri = new int [3] [3] [3];
		
	
		
		
		for(int i = 0 ; i < matrizTri.length ; i++) {
			for(int j = 0 ; j < matrizTri[i].length ; j++) {
				for(int k = 0 ; k< matrizTri[i][j].length ; k++) {
					System.out.println(" i = " + i + " - j = "+ j + " - k " + k);
					matrizTri[i][j][k]= i + j + k;
				}
			}
			
		}
		
		int soma = 0;
		int par = 0;
		int impar = 0;
		for(int i = 0 ; i < matrizTri.length ; i++) {
			for(int j = 0 ; j < matrizTri[i].length ; j++) {
				for(int k = 0 ; k < matrizTri[i][j].length ; k++) {
					
					soma+= matrizTri[i][j][k]= i + j + k;
					
					if(matrizTri[i][j][k] % 2 == 00) {
						par+=matrizTri[i][j][k]= i + j + k;
					}else {
						impar+=matrizTri[i][j][k]= i + j + k;
					}
				}
			}
			
		}
		System.out.println(soma);
		System.out.println(par);
		System.out.println(impar);
		
	
	
	
	
	}

}
