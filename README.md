# DSA
DSA for Java 


class Solution {
    public void reverseArray(int arr[]) {
        // code here
        int j=arr.length-1;
        int k=arr.length-1;
        int temp=0;
        for(int i=0;i<=j/2;i++)
        {
            temp=arr[i];
            arr[i]=arr[k];
            arr[k]=temp;
            k--;
        }
    }
}
