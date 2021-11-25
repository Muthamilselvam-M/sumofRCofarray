# sumofRCofarray

import java.util.Arrays;
public class Main{
    public static void main(String[] args){
        int[][] arr={{1,2,3,4},
                     {5,6,7,8},
                     {9,10,11,12}};
                     sumRow(arr);
                     sumColoumn(arr);
        
    }
    public static void sumRow(int[][] arr){
        int sum=0;
        for(int i=0;i<arr.length;i++){
             sum=0;
        for(int j=0;j<arr[i].length;j++){
                sum =sum + arr[i][j];
            }
            System.out.println("The sum of row " + sum);
        }}
        public static void sumColoumn(int[][] arr){
            int sum=0;
        for(int i=0;i<arr[0].length;i++){
        sum=0;
     for(int j=0;j<arr.length;j++){
                sum =sum + arr[j][i];
            }
            System.out.println("The sum of column "+ sum);
        }
    }}
