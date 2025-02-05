# team
#include<iostream>
using namespace std;
int main(){
    int n;
    cin>>n;
    int count=0;
    int Petya[n]={}; int Vasya[n]={}; int Tonya[n]={};
    for (int i=0; i<n;i++){
        cin>>Petya[i]>>Vasya[i]>>Tonya[i];
        if((Petya[i] + Vasya[i]+ Tonya[i])>=2){
            count++;
        }
    }
    cout<<count;
}
