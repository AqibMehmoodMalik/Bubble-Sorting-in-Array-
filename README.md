//# Bubble-Sorting-in-Array-
//This program will sort all random numbers to  into there positions  
public class arr {
    public static void printArray(int[] arr){
        for(int i=0;i<arr.length;i++){
            System.out.println(arr[i] + "");
        };
        
    }
    public static void main(String argus[]){
        //Bubble sorting
        int arr[]={7,8,3,1,2};
        for(int i=0; i<arr.length-1;i++){
           for(int j=0;j<arr.length-i-1;j++){
            if(arr[j]>arr[j+1]){
                //swapping
                int temp=arr[j];
                arr[j]=arr[j+1];
                arr[j+1]=temp;
                }
            }
        }
       printArray(arr);
    }
}
