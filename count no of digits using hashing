//**************count no of digit using hashing ***********
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n;
    cin>>n;
    int arr[n];
    //taking the input for the array 
    for(int i =0;i<n;i++){
        cin>>arr[i];
    }
    //precompute
    int hash[13]={0};
    for(int i =0;i<n;i++){
        hash[arr[i]]+=1;
    }
    
    int q;
    cin>>q;
    while(q--){
        int number;
        cin>>number;
        //fetch 
        cout<<hash[number] << endl;
        
    }
    return 0;
}

i/p

5
1 3 2 1 3
5
1
4
2
3
12

o/p
2
0
1
2
0
