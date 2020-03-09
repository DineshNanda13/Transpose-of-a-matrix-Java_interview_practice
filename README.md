# Transpose-of-a-matrix-Java_interview_practice
Java program to get a Transpose of a matrix

package transpose;

/**
 *
 * @author Dinesh Nanda
 */

public class TransposeOfMatrix {

    public static void main(String[] args) {
        
        int [][] a = {{4,2,5},{1,6,3},{9,7,8}};
        int [][] b;
        b = new int[a.length][a.length];
        
        for(int i = 0; i < a.length; i++){
            for(int j = 0; j < a.length; j++){
                b[i][j] = a[j][i];
            }
        }
        for(int i = 0; i < b.length; i++){
            for(int j = 0; j < b.length; j++){
                System.out.print(b[i][j] + " ");
            }
            System.out.println();
        }
    }
}
