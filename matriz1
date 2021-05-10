package ed.br.edu.unidesc.alunos.estruturadados;
import java.util.Random;

//-----------------------------------------------------//
public class Main {
    static int [][] gerarMatriz(int A, int B){
        int [][] matriz = new int [A][B];
        Random valores = new Random();
        for (int i = 0; i < matriz.length; i++){
            for (int j = 0; j < matriz[0].length; j++) {
                matriz [i][j] = valores.nextInt(100);
            }
        }
        return matriz;
    }
//-----------------------------------------------------//
    static void mostrarMatriz(int[][] matriz){
        for (int i = 0; i < matriz.length; i++){
            for (int j = 0; j < matriz[i].length; j++) {
                System.out.print(matriz[i][j] +"\t");
            }
            System.out.print("\n");
        }
    }
//-----------------------------------------------------//
    static int[][] transposta(int[][] matriz){
        int [][] mTransposta = new int [matriz[0].length][matriz.length];
        for (int i = 0; i < mTransposta.length; i++){
            for (int j = 0; j < mTransposta[0].length; j++) {
                mTransposta [i][j] = matriz [j][i];
            }
        }
        return  mTransposta;
    }
//-----------------------------------------------------//
    public static void main(String[] args) {
        System.out.print("\nMatriz normal\n\n");
        int [][] matriz = gerarMatriz(4,5);
        mostrarMatriz(matriz);
        System.out.print("\nMatriz transposta\n\n");
        int [][] transposta = transposta(matriz);
        mostrarMatriz(transposta);
    }
}
