#include<bits/stdc++.h>
using namespace std;

int main(){
    int n;
    cin>>n;
    
    for(int i =1;i<=n;i++){
        if(n%i==0){                   //unit operation
            cout<<i<<endl; 
        }
        
    }
}

// time complexity is o(n)

Another of way of doing is 


#include<bits/stdc++.h>
using namespace std;
int main(){
    int n;
    cin>>n;
    vector<int> ls; //to store dynamically
    
    //why sqrt = because we need to print till square only (ex: n = 36, then till 6 only we have to print)
    for(int i =1;i<=sqrt(n);i++){
        
        if(n%i == 0){
              ls.push_back(i);  //storing i in vector container
              
              if((n/i)!=i){
                  ls.push_back(n/i); // storing n/i in vectot container 
              }
        }
    }
    sort(ls.begin(),ls.end());  // sorting the random values of container
    
    for(auto it:ls) cout<<it<<" "; // iterating through the container 
    
    
}


