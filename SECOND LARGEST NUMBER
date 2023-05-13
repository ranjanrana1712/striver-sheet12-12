BRUTE FORCE
WE USE QUICK SORT TO SORT ALL THE ELEMENTS AND THEN RUN FOR LOOP FROM N-2.
APPLICABLE ONLY FOR ARRAY WITH NO DUPLICATES
ITME COMPLEXITY IS O(NLOGN) + O(N)

BETTER APPROACH
WE USE 2 FOR LOOPS 
1) FIRST FOR LOOP IS TO FIND THE LARGEST ELEMENT OF THE ARRAY 
2) SECOND FOR LOOP IS TO FINS THE SECOND LARGEST ELEMENT IN THE ARRAY 
TIME COMPLEXITY IS 0(2N)



OPTIMAL APPROACH



#include<bits/stdc++.h>
using namespace std;
void getElements(int arr[],int n){
    if(n ==1 || n ==0)
    
    
    cout<< -1 << " "<< -1 << endl;
    
    int small = INT_MAX,second_small = INT_MAX;
    
    int large = INT_MIN,second_large = INT_MIN;
    
    int i =0;
    for(int i =0;i<n;i++){
        small=min(small,arr[i]);
        large=max(large,arr[i]);
        
    }
    
    for(int i =0;i<n;i++){
        if(arr[i] < second_small && arr[i]!=small)
            second_small=arr[i];
        if(arr[i]>second_large && arr[i]!=large)
            second_large = arr[i];
    }
    
    cout<<"second small "<<second_small <<endl;
    cout<<" second large"<<second_large <<endl;
    
}



int main(){
    int arr[]={1,2,4,6,7,5};
    int n = sizeof(arr) / sizeof(arr[0]);
    
    getElements(arr,n);
    return 0;
}



TIME COMPLEXITY IS O(N)
