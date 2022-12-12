# pointer-function

// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int getsum(int arr[], int n){
    int sum=0;
    for(int i=0;i<n;i++){
        sum += arr[i];
    }
    return sum;
}
int main() {
    // Write C++ code here
    int arr[4]={2,6,9,10};
    cout<<sizeof(arr)<<endl;
    //char arr2[10]="abcj";
    //cout<<sizeof(arr2)<<endl;
    //cout<<&arr2<<endl;
    
    cout<<" sum is "<<getsum(arr,4)<<endl;
    return 0;
}
