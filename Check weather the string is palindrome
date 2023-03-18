//using recursion to check weather the string is palindrome


logic -- comparing left half with right half 
#include<bits/stdc++.h>
#include<string.h>
using namespace std;

bool f(int i, string &s){
    //returnn true if index size is greater or equal  to half of size of string
    
    if(i>=s.size() /2)  return true;
    //if below condition if false it call another functtion.if not equal condition is true then returns false 
    
    if (s[i] != s[s.size()-i-1]) return false;
    //calling function with increment in index size .
    f(i+1,s);
}
int main(){
    string s = "madam";
    cout<<f(0,s);
    return 0;
}

**************for differrent types of cases**************

class Solution {
public:
    bool isPalindrome(string s) {
        int start = 0, end = s.size()-1;
        while(start <= end){
            // lowercase the char
            char startChar =tolower(s[start]);
            char lastChar = tolower(s[end]);

            // if not alpha numeric increase/decrement pointer respectiverly
            if(!isalnum(int(startChar))){
                start++;
                continue;
            }
            if(!isalnum(int(lastChar))){
                end--;
                continue;
            }

            // if char match go for next char
            if(startChar==lastChar){
                start++;
                end--;
            }else{
                return false;
            }
        }
        return true;
    }
};
