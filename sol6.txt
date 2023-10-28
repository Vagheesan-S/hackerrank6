import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        String result;
        int N = s.nextInt();
        if(N%2 == 0) {
            if( (N >=2 && N <=5) || N > 20) {
                result = "Not Weird";
            } else {
                result = "Weird";
            }
        } else {
            result = "Weird";
        }
        System.out.println(result);
    }
}